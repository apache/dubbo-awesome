# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.249 ops/ms
# Warmup Iteration   2: 8.778 ops/ms
# Warmup Iteration   3: 9.955 ops/ms
Iteration   1: 10.442 ops/ms
Iteration   2: 10.571 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.489 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (10.442, 10.489, 10.571), stdev = 0.071
  CI (99.9%): [9.188, 11.789] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.426 ops/ms
# Warmup Iteration   2: 10.563 ops/ms
# Warmup Iteration   3: 11.121 ops/ms
Iteration   1: 11.380 ops/ms
Iteration   2: 11.375 ops/ms
Iteration   3: 11.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.345 ±(99.9%) 1.036 ops/ms [Average]
  (min, avg, max) = (11.279, 11.345, 11.380), stdev = 0.057
  CI (99.9%): [10.308, 12.381] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.453 ops/ms
# Warmup Iteration   2: 9.871 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.699 ±(99.9%) 0.636 ops/ms [Average]
  (min, avg, max) = (10.664, 10.699, 10.734), stdev = 0.035
  CI (99.9%): [10.063, 11.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.672 ops/ms
# Warmup Iteration   2: 8.209 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.290 ops/ms
Iteration   2: 8.126 ops/ms
Iteration   3: 8.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 1.507 ops/ms [Average]
  (min, avg, max) = (8.126, 8.213, 8.290), stdev = 0.083
  CI (99.9%): [6.706, 9.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.002 ms/op
Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.025 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (2.974, 3.025, 3.072), stdev = 0.049
  CI (99.9%): [2.129, 3.921] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.003 ms/op
Iteration   1: 2.848 ±(99.9%) 0.004 ms/op
Iteration   2: 2.906 ±(99.9%) 0.003 ms/op
Iteration   3: 2.926 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.893 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (2.848, 2.893, 2.926), stdev = 0.041
  CI (99.9%): [2.150, 3.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 3.001 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.101 ms/op [Average]
  (min, avg, max) = (3.001, 3.007, 3.011), stdev = 0.006
  CI (99.9%): [2.906, 3.108] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.476 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.044 ms/op
Iteration   1: 3.935 ±(99.9%) 0.017 ms/op
Iteration   2: 3.905 ±(99.9%) 0.009 ms/op
Iteration   3: 3.915 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.905, 3.918, 3.935), stdev = 0.015
  CI (99.9%): [3.641, 4.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.177 ms/op
                 createUser·p0.9999: 13.006 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.778 ms/op
                 createUser·p0.9999: 27.830 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.686 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  13.910 ms/op
                 createUser·p0.9999: 20.392 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316155
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26074 
    [ 2.500,  5.000) = 288518 
    [ 5.000,  7.500) = 1153 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.809 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     28.667 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.066 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
Iteration   1: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.002 ms/op
                 existUser·p0.999:  6.576 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   2: 2.866 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 14.642 ms/op
                 existUser·p1.00:   15.024 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  11.754 ms/op
                 existUser·p0.9999: 16.563 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331051
  mean =      2.898 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44344 
    [ 2.500,  5.000) = 285774 
    [ 5.000,  7.500) = 569 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.108 ms/op
     p(99.9000) =      8.631 ms/op
     p(99.9900) =     20.870 ms/op
     p(99.9990) =     22.053 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.584 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  7.873 ms/op
                 getUser·p0.9999: 16.777 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.770 ms/op
                 getUser·p0.9999: 17.211 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.281 ms/op
                 getUser·p0.999:  7.552 ms/op
                 getUser·p0.9999: 17.573 ms/op
                 getUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320573
  mean =      2.992 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 816 
    [ 1.250,  2.500) = 29266 
    [ 2.500,  3.750) = 273850 
    [ 3.750,  5.000) = 15182 
    [ 5.000,  6.250) = 695 
    [ 6.250,  7.500) = 420 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 86 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.589 ms/op
     p(99.9900) =     17.201 ms/op
     p(99.9990) =     19.615 ms/op
     p(99.9999) =     19.759 ms/op
    p(100.0000) =     19.759 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.779 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
Iteration   1: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 19.258 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.822 ms/op
                 listUser·p0.999:  15.438 ms/op
                 listUser·p0.9999: 20.398 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   3: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.746 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 21.982 ms/op
                 listUser·p1.00:   22.249 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244485
  mean =      3.923 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3642 
    [ 2.500,  5.000) = 220097 
    [ 5.000,  7.500) = 19458 
    [ 7.500, 10.000) = 714 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     15.213 ms/op
     p(99.9900) =     21.232 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.489 ± 1.301  ops/ms
ClientGrpc.existUser                       thrpt       3  11.345 ± 1.036  ops/ms
ClientGrpc.getUser                         thrpt       3  10.699 ± 0.636  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 1.507  ops/ms
ClientGrpc.createUser                       avgt       3   3.025 ± 0.896   ms/op
ClientGrpc.existUser                        avgt       3   2.893 ± 0.744   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.101   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.277   ms/op
ClientGrpc.createUser                     sample  316155   3.036 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.799           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.809           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.001           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.803           ms/op
ClientGrpc.existUser                      sample  331051   2.898 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.676           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.108           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.631           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.870           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  320573   2.992 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.584           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.589           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.201           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.759           ms/op
ClientGrpc.listUser                       sample  244485   3.923 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.213           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.232           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.249           ms/op
