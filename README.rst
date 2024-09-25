A tool to perform regression tests for REST

Usage: rest_regression [OPTIONS]

Options:
  -r, --regression_directory <regression_directory>
          The directory that contains selected regression tasks [default: $REST_HOME/utilities/rest_regression/bench_pool]
  -w, --working_directory <working_directory>
          The working directory to store the regression output files [default: ./work_pool]
  -c, --rest_mode <rest_mode>
          The version of REST binary to invoke: "release" or "debug"  [default: release]
  -p, --rest_path <rest_path>
          The absolute path to find the `rest` binary [default: $REST_HOME/target/`rest_mode`/rest]
  -h, --help
          Print help
  -V, --version
          Print version
