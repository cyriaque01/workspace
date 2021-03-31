# workspace
a basic introduction to learning git
pid_t pid;
pid_t pid;
pid = fork();
pid = fork();
if (pid<0){
if (pid<0){
  print("fork failled");
  printf("fork failled");
  }
  }
 if(pid==0){
 if(pid==0){
  print("i am the child with pid%d\n",(int)getpid(),(int)getppid());
  printf("i am the child with pid%d\n",(int)getpid(),(int)getppid());
  }
  }
  else(pid>0){
  else(pid>0){
    print("i am the parent with pid %\n", (int)getpid());
    printf("i am the parent with pid %\n", (int)getpid());
    }
    }
    return 0
