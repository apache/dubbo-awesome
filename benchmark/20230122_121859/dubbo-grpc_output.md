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
# Warmup Iteration   1: 4.762 ops/ms
# Warmup Iteration   2: 9.874 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.435 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (10.281, 10.435, 10.581), stdev = 0.150
  CI (99.9%): [7.695, 13.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.513 ops/ms
# Warmup Iteration   2: 11.118 ops/ms
# Warmup Iteration   3: 10.943 ops/ms
Iteration   1: 11.063 ops/ms
Iteration   2: 11.214 ops/ms
Iteration   3: 11.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.112 ±(99.9%) 1.617 ops/ms [Average]
  (min, avg, max) = (11.058, 11.112, 11.214), stdev = 0.089
  CI (99.9%): [9.495, 12.729] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 10.411 ops/ms
# Warmup Iteration   3: 10.602 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.479 ±(99.9%) 2.734 ops/ms [Average]
  (min, avg, max) = (10.367, 10.479, 10.649), stdev = 0.150
  CI (99.9%): [7.745, 13.212] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.901 ops/ms
# Warmup Iteration   2: 7.870 ops/ms
# Warmup Iteration   3: 8.112 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.222 ±(99.9%) 0.422 ops/ms [Average]
  (min, avg, max) = (8.195, 8.222, 8.236), stdev = 0.023
  CI (99.9%): [7.800, 8.644] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.069 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.010 ms/op
Iteration   1: 2.943 ±(99.9%) 0.002 ms/op
Iteration   2: 3.126 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 1.812 ms/op [Average]
  (min, avg, max) = (2.943, 3.057, 3.126), stdev = 0.099
  CI (99.9%): [1.245, 4.870] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.653 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.004 ms/op
Iteration   1: 2.928 ±(99.9%) 0.001 ms/op
Iteration   2: 2.932 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.926 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (2.917, 2.926, 2.932), stdev = 0.008
  CI (99.9%): [2.779, 3.072] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.002 ms/op
Iteration   1: 3.062 ±(99.9%) 0.004 ms/op
Iteration   2: 2.959 ±(99.9%) 0.004 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (2.959, 3.027, 3.062), stdev = 0.059
  CI (99.9%): [1.947, 4.108] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.111 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.008 ms/op
Iteration   1: 3.975 ±(99.9%) 0.034 ms/op
Iteration   2: 3.929 ±(99.9%) 0.017 ms/op
Iteration   3: 3.978 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.929, 3.961, 3.978), stdev = 0.028
  CI (99.9%): [3.453, 4.469] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.238 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.094 ms/op
                 createUser·p0.9999: 15.437 ms/op
                 createUser·p1.00:   15.778 ms/op

Iteration   2: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.790 ms/op
                 createUser·p0.9999: 13.512 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  10.098 ms/op
                 createUser·p0.9999: 23.453 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308127
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28405 
    [ 2.500,  5.000) = 278755 
    [ 5.000,  7.500) = 614 
    [ 7.500, 10.000) = 120 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.238 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      8.101 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.552 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.911 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.649 ms/op
                 existUser·p0.9999: 11.750 ms/op
                 existUser·p1.00:   11.960 ms/op

Iteration   2: 2.913 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.636 ms/op
                 existUser·p0.9999: 25.101 ms/op
                 existUser·p1.00:   26.051 ms/op

Iteration   3: 2.957 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.493 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.077 ms/op
                 existUser·p0.9999: 14.905 ms/op
                 existUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327300
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50279 
    [ 2.500,  5.000) = 276413 
    [ 5.000,  7.500) = 403 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.493 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.162 ms/op
     p(99.9000) =      6.046 ms/op
     p(99.9900) =     18.310 ms/op
     p(99.9990) =     25.988 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 3.730 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 24.337 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.576 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.672 ms/op
                 getUser·p0.9999: 16.924 ms/op
                 getUser·p1.00:   17.498 ms/op

Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.794 ms/op
                 getUser·p0.9999: 17.410 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316189
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27842 
    [ 2.500,  5.000) = 287446 
    [ 5.000,  7.500) = 675 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.962 ms/op
     p(99.9900) =     23.467 ms/op
     p(99.9990) =     24.889 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 5.013 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.090 ±(99.9%) 0.012 ms/op
Iteration   1: 3.987 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 18.218 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   2: 4.106 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.813 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 18.167 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 4.104 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 41.825 ms/op
                 listUser·p1.00:   46.989 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236200
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 199459 
    [ 5.000, 10.000) = 36337 
    [10.000, 15.000) = 185 
    [15.000, 20.000) = 179 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     41.050 ms/op
     p(99.9990) =     43.107 ms/op
     p(99.9999) =     46.989 ms/op
    p(100.0000) =     46.989 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.435 ± 2.740  ops/ms
ClientGrpc.existUser                       thrpt       3  11.112 ± 1.617  ops/ms
ClientGrpc.getUser                         thrpt       3  10.479 ± 2.734  ops/ms
ClientGrpc.listUser                        thrpt       3   8.222 ± 0.422  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 1.812   ms/op
ClientGrpc.existUser                        avgt       3   2.926 ± 0.147   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 1.081   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 0.508   ms/op
ClientGrpc.createUser                     sample  308127   3.115 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.238           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.944           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.101           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.577           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  327300   2.934 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.493           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.162           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.046           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.310           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.051           ms/op
ClientGrpc.getUser                        sample  316189   3.034 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.545           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.962           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.467           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.002           ms/op
ClientGrpc.listUser                       sample  236200   4.065 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.764           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          41.050           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          46.989           ms/op
