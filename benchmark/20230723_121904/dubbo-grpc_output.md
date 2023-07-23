# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.146 ops/ms
# Warmup Iteration   2: 8.953 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 10.405 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.520 ±(99.9%) 2.835 ops/ms [Average]
  (min, avg, max) = (10.405, 10.520, 10.697), stdev = 0.155
  CI (99.9%): [7.685, 13.355] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.273 ops/ms
# Warmup Iteration   2: 10.564 ops/ms
# Warmup Iteration   3: 10.770 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.972 ops/ms
Iteration   3: 11.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.972 ±(99.9%) 2.411 ops/ms [Average]
  (min, avg, max) = (10.840, 10.972, 11.104), stdev = 0.132
  CI (99.9%): [8.561, 13.383] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.230 ops/ms
# Warmup Iteration   2: 9.942 ops/ms
# Warmup Iteration   3: 10.326 ops/ms
Iteration   1: 10.272 ops/ms
Iteration   2: 10.474 ops/ms
Iteration   3: 10.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.376 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (10.272, 10.376, 10.474), stdev = 0.102
  CI (99.9%): [8.524, 12.228] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.546 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 8.133 ops/ms
Iteration   2: 8.098 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.107 ±(99.9%) 0.421 ops/ms [Average]
  (min, avg, max) = (8.090, 8.107, 8.133), stdev = 0.023
  CI (99.9%): [7.687, 8.528] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.182 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.002 ms/op
Iteration   1: 3.093 ±(99.9%) 0.003 ms/op
Iteration   2: 3.035 ±(99.9%) 0.003 ms/op
Iteration   3: 2.987 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.038 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (2.987, 3.038, 3.093), stdev = 0.053
  CI (99.9%): [2.066, 4.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.003 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.902 ±(99.9%) 0.002 ms/op
Iteration   3: 2.920 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.902, 2.910, 2.920), stdev = 0.009
  CI (99.9%): [2.748, 3.072] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.424 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
Iteration   3: 3.091 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.072 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.028, 3.072, 3.098), stdev = 0.039
  CI (99.9%): [2.370, 3.775] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.030 ms/op
Iteration   1: 4.009 ±(99.9%) 0.018 ms/op
Iteration   2: 3.905 ±(99.9%) 0.008 ms/op
Iteration   3: 3.898 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.938 ±(99.9%) 1.133 ms/op [Average]
  (min, avg, max) = (3.898, 3.938, 4.009), stdev = 0.062
  CI (99.9%): [2.805, 5.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.349 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
Iteration   1: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.867 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.667 ms/op
                 createUser·p0.9999: 18.763 ms/op
                 createUser·p1.00:   19.333 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.819 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.455 ms/op
                 createUser·p0.9999: 15.133 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  10.696 ms/op
                 createUser·p0.9999: 16.208 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311082
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 843 
    [ 1.250,  2.500) = 20709 
    [ 2.500,  3.750) = 266942 
    [ 3.750,  5.000) = 20992 
    [ 5.000,  6.250) = 971 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 101 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.384 ms/op
     p(99.9900) =     17.036 ms/op
     p(99.9990) =     18.936 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.291 ms/op
                 existUser·p0.999:  5.734 ms/op
                 existUser·p0.9999: 11.935 ms/op
                 existUser·p1.00:   12.354 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 16.320 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.987 ms/op
                 existUser·p0.9999: 20.814 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325388
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29728 
    [ 2.500,  5.000) = 294635 
    [ 5.000,  7.500) = 718 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     19.095 ms/op
     p(99.9990) =     21.487 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.268 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
Iteration   1: 3.110 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.648 ms/op
                 getUser·p0.999:  7.552 ms/op
                 getUser·p0.9999: 13.798 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  6.538 ms/op
                 getUser·p0.9999: 13.800 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.435 ms/op
                 getUser·p0.9999: 16.755 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309857
  mean =      3.097 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 500 
    [ 1.250,  2.500) = 19412 
    [ 2.500,  3.750) = 263973 
    [ 3.750,  5.000) = 24411 
    [ 5.000,  6.250) = 995 
    [ 6.250,  7.500) = 312 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     15.909 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.775 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.390 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.054 ±(99.9%) 0.012 ms/op
Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.025 ms/op
                 listUser·p0.9999: 21.952 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.668 ms/op
                 listUser·p0.9999: 19.203 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 3.907 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.199 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.567 ms/op
                 listUser·p0.9999: 20.494 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242338
  mean =      3.961 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3952 
    [ 2.500,  5.000) = 213662 
    [ 5.000,  7.500) = 23567 
    [ 7.500, 10.000) = 706 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     21.251 ms/op
     p(99.9990) =     22.404 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.520 ± 2.835  ops/ms
ClientGrpc.existUser                       thrpt       3  10.972 ± 2.411  ops/ms
ClientGrpc.getUser                         thrpt       3  10.376 ± 1.852  ops/ms
ClientGrpc.listUser                        thrpt       3   8.107 ± 0.421  ops/ms
ClientGrpc.createUser                       avgt       3   3.038 ± 0.972   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 0.162   ms/op
ClientGrpc.getUser                          avgt       3   3.072 ± 0.702   ms/op
ClientGrpc.listUser                         avgt       3   3.938 ± 1.133   ms/op
ClientGrpc.createUser                     sample  311082   3.084 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.658           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.384           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.036           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.333           ms/op
ClientGrpc.existUser                      sample  325388   2.950 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.898           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.095           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  309857   3.097 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.792           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.193           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.909           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  242338   3.961 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.926           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.251           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.479           ms/op
