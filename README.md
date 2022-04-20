# kafka-mini-project

## Steps to run the application

1. From the Bash shell run:
```bash
$ chmod 777 start.sh
$ ./start.sh
```

2. In another tab of Bash shell, run:
```bash
$ chmod 777 start_main_docker_compose.sh
$ ./start_main_docker_compose.sh
```

Then we will see this output:
! [Screen Shot 2022-04-19 at 9 27 33 PM](https://user-images.githubusercontent.com/72058053/164150706-795815db-516c-41c8-ae53-fa1cee82ce0d.png)

3. Read the whole topic, run this command:
```bash
$ chmod 777 read_whole_topic.sh
$ ./read_whole_topic.sh
```


4. Run `Ctrl + C` to stop the `kafka-console-consumer`