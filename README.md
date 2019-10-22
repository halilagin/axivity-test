# radarad-device-axivity

This project presents a test environment for the parser developed by [Biobank Accelerometer Analysis](https://github.com/activityMonitoring/biobankAccelerometerAnalysis). The test environment consists of a Dockerified ubuntu OS with a JDK installed. The source code of Biobank Accelerometer Analysis is mounted under the directory **workdir**. To have the test environment please follow the commands below.

## start the docker container (virtual machine)

```bash
sh dcup.sh
```

## Attach a terminal to the container 
```bash
sh dcterminal.sh
```

## Download the sample cwa files
```bash
cd biobankAccelerometerAnalysis
sh utilities/downloadDataModels.sh
```


## Windows environment

For windows environment, run the content of the dcup.sh and dcterminal.sh, which are actually docker commands.
