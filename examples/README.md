# Tests to understand the working of PyDSS

1. Run the IEEE123 Feeder model
   - Created a new empty project: `pydss create-project --project=my-project --scenarios="scenario1,scenario2" --path=./pydss-projects`
   - Downloaded the OpenDSS model from the OpenDSS Github [sub-directory](https://github.com/tshort/OpenDSS/tree/master/Distrib/IEEETestCases/123Bus)
   - Added the directory to the PyDSS project directory in the `DSSfiles` sub-directory.
   - Changed `dss_file = "123Bus/IEEE123Master.dss"` in `my-project\simulation.toml`
   - In `simulation.toml`, changed the `export_results` setting to `true`.
   - Run the command `pydss run ./pydss-projects/my-project/`, and it will store the files in the respective scenario directories.
