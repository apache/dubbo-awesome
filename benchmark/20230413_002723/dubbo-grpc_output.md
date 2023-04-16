# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.521 ops/ms
# Warmup Iteration   2: 8.220 ops/ms
# Warmup Iteration   3: 9.927 ops/ms
Iteration   1: 10.119 ops/ms
Iteration   2: 10.235 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.191 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (10.119, 10.191, 10.235), stdev = 0.063
  CI (99.9%): [9.050, 11.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.918 ops/ms
# Warmup Iteration   2: 10.313 ops/ms
# Warmup Iteration   3: 10.653 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.738 ±(99.9%) 3.443 ops/ms [Average]
  (min, avg, max) = (10.578, 10.738, 10.946), stdev = 0.189
  CI (99.9%): [7.295, 14.180] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 5.915 ops/ms
# Warmup Iteration   2: 9.809 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.205 ops/ms
Iteration   2: 10.280 ops/ms
Iteration   3: 10.326 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.271 ±(99.9%) 1.113 ops/ms [Average]
  (min, avg, max) = (10.205, 10.271, 10.326), stdev = 0.061
  CI (99.9%): [9.158, 11.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.215 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 7.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.929 ±(99.9%) 0.613 ops/ms [Average]
  (min, avg, max) = (7.891, 7.929, 7.954), stdev = 0.034
  CI (99.9%): [7.315, 8.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.002 ms/op
Iteration   1: 3.032 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.071 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.060 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.032, 3.060, 3.077), stdev = 0.025
  CI (99.9%): [2.612, 3.508] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.699 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.002 ms/op
Iteration   1: 2.907 ±(99.9%) 0.002 ms/op
Iteration   2: 2.852 ±(99.9%) 0.003 ms/op
Iteration   3: 2.811 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.856 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (2.811, 2.856, 2.907), stdev = 0.048
  CI (99.9%): [1.978, 3.735] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.277 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.002 ms/op
Iteration   1: 3.015 ±(99.9%) 0.004 ms/op
Iteration   2: 3.126 ±(99.9%) 0.001 ms/op
Iteration   3: 3.031 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.057 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.015, 3.057, 3.126), stdev = 0.060
  CI (99.9%): [1.968, 4.146] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.458 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.021 ms/op
Iteration   1: 3.913 ±(99.9%) 0.009 ms/op
Iteration   2: 4.039 ±(99.9%) 0.022 ms/op
Iteration   3: 4.007 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.986 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (3.913, 3.986, 4.039), stdev = 0.066
  CI (99.9%): [2.788, 5.185] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.443 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.362 ms/op
                 createUser·p0.9999: 13.608 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 3.082 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.375 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.137 ms/op
                 createUser·p0.9999: 14.772 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.296 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  8.962 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313144
  mean =      3.066 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 495 
    [ 1.250,  2.500) = 20456 
    [ 2.500,  3.750) = 275733 
    [ 3.750,  5.000) = 14990 
    [ 5.000,  6.250) = 608 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.296 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.545 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
Iteration   1: 2.855 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.420 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.422 ms/op
                 existUser·p0.9999: 14.500 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.706 ms/op
                 existUser·p0.9999: 14.730 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 18.162 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330429
  mean =      2.905 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 887 
    [ 1.250,  2.500) = 37968 
    [ 2.500,  3.750) = 282072 
    [ 3.750,  5.000) = 8213 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 308 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.062 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.930 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.525 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  11.532 ms/op
                 getUser·p0.9999: 20.997 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.819 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.072 ms/op
                 getUser·p0.9999: 14.495 ms/op
                 getUser·p1.00:   15.958 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  7.422 ms/op
                 getUser·p0.9999: 17.516 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316868
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17164 
    [ 2.500,  5.000) = 298241 
    [ 5.000,  7.500) = 1133 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.595 ms/op
     p(99.9900) =     20.228 ms/op
     p(99.9990) =     22.042 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.519 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.011 ms/op
Iteration   1: 4.084 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.092 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 17.077 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.034 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 18.252 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 3.978 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 20.145 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239603
  mean =      4.011 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1774 
    [ 2.500,  5.000) = 214115 
    [ 5.000,  7.500) = 22169 
    [ 7.500, 10.000) = 1121 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     18.880 ms/op
     p(99.9990) =     20.683 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.191 ± 1.141  ops/ms
ClientGrpc.existUser                       thrpt       3  10.738 ± 3.443  ops/ms
ClientGrpc.getUser                         thrpt       3  10.271 ± 1.113  ops/ms
ClientGrpc.listUser                        thrpt       3   7.929 ± 0.613  ops/ms
ClientGrpc.createUser                       avgt       3   3.060 ± 0.448   ms/op
ClientGrpc.existUser                        avgt       3   2.856 ± 0.878   ms/op
ClientGrpc.getUser                          avgt       3   3.057 ± 1.089   ms/op
ClientGrpc.listUser                         avgt       3   3.986 ± 1.199   ms/op
ClientGrpc.createUser                     sample  313144   3.066 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.296           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.545           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.465           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.776           ms/op
ClientGrpc.existUser                      sample  330429   2.905 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.654           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.062           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.465           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.038           ms/op
ClientGrpc.getUser                        sample  316868   3.028 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.574           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.595           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.228           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.184           ms/op
ClientGrpc.listUser                       sample  239603   4.011 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.955           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.880           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.103           ms/op