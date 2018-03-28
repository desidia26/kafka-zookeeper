To startup the kafka cluster, run fireUpKafka.sh (it has a sudo in it until I can figure out why it has issue with writing to its own directory)

Once the kafka server is running it will occupy that terminal window with its logs.

To shut down the cluster, Ctrl+c. Then to shutdown the zookeeper it was running on, run shutdownZookeeper.sh
