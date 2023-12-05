# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ops/ms
# Warmup Iteration   2: 11.917 ops/ms
# Warmup Iteration   3: 12.033 ops/ms
Iteration   1: 12.275 ops/ms
Iteration   2: 12.441 ops/ms
Iteration   3: 12.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.423 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (12.275, 12.423, 12.554), stdev = 0.140
  CI (99.9%): [9.870, 14.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.808 ops/ms
# Warmup Iteration   2: 12.665 ops/ms
# Warmup Iteration   3: 12.717 ops/ms
Iteration   1: 12.686 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.731 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (12.686, 12.731, 12.762), stdev = 0.040
  CI (99.9%): [12.004, 13.459] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.701 ops/ms
# Warmup Iteration   2: 12.401 ops/ms
# Warmup Iteration   3: 12.550 ops/ms
Iteration   1: 12.797 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.702 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (12.603, 12.702, 12.797), stdev = 0.097
  CI (99.9%): [10.928, 14.476] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.441 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.347 ops/ms
Iteration   1: 10.393 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.263 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.369 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (10.263, 10.369, 10.452), stdev = 0.096
  CI (99.9%): [8.609, 12.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.136 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.570 ±(99.9%) 0.004 ms/op
Iteration   1: 2.619 ±(99.9%) 0.003 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.574 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (2.546, 2.574, 2.619), stdev = 0.039
  CI (99.9%): [1.857, 3.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
Iteration   3: 2.534 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.533 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (2.509, 2.533, 2.556), stdev = 0.023
  CI (99.9%): [2.108, 2.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.004 ms/op
Iteration   1: 2.581 ±(99.9%) 0.005 ms/op
Iteration   2: 2.561 ±(99.9%) 0.004 ms/op
Iteration   3: 2.548 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.563 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.548, 2.563, 2.581), stdev = 0.017
  CI (99.9%): [2.258, 2.868] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.834 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
Iteration   2: 3.020 ±(99.9%) 0.006 ms/op
Iteration   3: 3.024 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.020, 3.029, 3.043), stdev = 0.012
  CI (99.9%): [2.804, 3.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.681 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.540 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  11.354 ms/op
                 createUser·p0.9999: 13.770 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  9.306 ms/op
                 createUser·p0.9999: 12.517 ms/op
                 createUser·p1.00:   12.911 ms/op

Iteration   3: 2.543 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  9.018 ms/op
                 createUser·p0.9999: 11.321 ms/op
                 createUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378261
  mean =      2.535 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 181648 
    [ 2.500,  3.750) = 192198 
    [ 3.750,  5.000) = 3506 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.667 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.759 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.987 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.695 ms/op
                 existUser·p0.999:  6.967 ms/op
                 existUser·p0.9999: 14.221 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.547 ms/op
                 existUser·p0.999:  5.669 ms/op
                 existUser·p0.9999: 13.827 ms/op
                 existUser·p1.00:   14.762 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.508 ms/op
                 existUser·p0.9999: 12.763 ms/op
                 existUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388527
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 194416 
    [ 2.500,  3.750) = 190481 
    [ 3.750,  5.000) = 2566 
    [ 5.000,  6.250) = 601 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     13.781 ms/op
     p(99.9990) =     14.659 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.635 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.006 ms/op
Iteration   1: 2.510 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.855 ms/op
                 getUser·p0.999:  11.487 ms/op
                 getUser·p0.9999: 13.488 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.540 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  9.486 ms/op
                 getUser·p0.9999: 12.515 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  8.633 ms/op
                 getUser·p0.9999: 11.624 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380254
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 185877 
    [ 2.500,  3.750) = 188746 
    [ 3.750,  5.000) = 4415 
    [ 5.000,  6.250) = 723 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.030 ms/op
     p(99.9000) =      8.663 ms/op
     p(99.9900) =     13.255 ms/op
     p(99.9990) =     14.146 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.407 ms/op
                 listUser·p0.9999: 11.315 ms/op
                 listUser·p1.00:   12.435 ms/op

Iteration   2: 3.074 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 11.921 ms/op
                 listUser·p1.00:   13.730 ms/op

Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.785 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.521 ms/op
                 listUser·p0.999:  8.602 ms/op
                 listUser·p0.9999: 11.674 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312317
  mean =      3.071 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 80648 
    [ 2.500,  3.750) = 188883 
    [ 3.750,  5.000) = 35191 
    [ 5.000,  6.250) = 6268 
    [ 6.250,  7.500) = 579 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.626 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     11.682 ms/op
     p(99.9990) =     12.737 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.423 ± 2.554  ops/ms
ClientPb.existUser                       thrpt       3  12.731 ± 0.728  ops/ms
ClientPb.getUser                         thrpt       3  12.702 ± 1.774  ops/ms
ClientPb.listUser                        thrpt       3  10.369 ± 1.760  ops/ms
ClientPb.createUser                       avgt       3   2.574 ± 0.717   ms/op
ClientPb.existUser                        avgt       3   2.533 ± 0.425   ms/op
ClientPb.getUser                          avgt       3   2.563 ± 0.305   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.225   ms/op
ClientPb.createUser                     sample  378261   2.535 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.241           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.156           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.778           ms/op
ClientPb.existUser                      sample  388527   2.469 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.936           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.781           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.811           ms/op
ClientPb.getUser                        sample  380254   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.952           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.663           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.255           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  312317   3.071 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.785           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.626           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.682           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.730           ms/op
