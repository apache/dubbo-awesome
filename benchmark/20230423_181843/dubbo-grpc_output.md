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
# Warmup Iteration   1: 3.974 ops/ms
# Warmup Iteration   2: 8.960 ops/ms
# Warmup Iteration   3: 10.363 ops/ms
Iteration   1: 10.478 ops/ms
Iteration   2: 10.643 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.675 ±(99.9%) 3.907 ops/ms [Average]
  (min, avg, max) = (10.478, 10.675, 10.903), stdev = 0.214
  CI (99.9%): [6.768, 14.582] (assumes normal distribution)


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
# Warmup Iteration   1: 7.359 ops/ms
# Warmup Iteration   2: 10.694 ops/ms
# Warmup Iteration   3: 10.893 ops/ms
Iteration   1: 11.027 ops/ms
Iteration   2: 11.096 ops/ms
Iteration   3: 11.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.095 ±(99.9%) 1.227 ops/ms [Average]
  (min, avg, max) = (11.027, 11.095, 11.161), stdev = 0.067
  CI (99.9%): [9.868, 12.321] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.836 ops/ms
# Warmup Iteration   2: 10.305 ops/ms
# Warmup Iteration   3: 10.495 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.652 ops/ms
Iteration   3: 10.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.667 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (10.641, 10.667, 10.708), stdev = 0.036
  CI (99.9%): [10.012, 11.322] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.645 ops/ms
# Warmup Iteration   2: 7.853 ops/ms
# Warmup Iteration   3: 7.951 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.278 ops/ms
Iteration   3: 8.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.148 ±(99.9%) 2.280 ops/ms [Average]
  (min, avg, max) = (8.029, 8.148, 8.278), stdev = 0.125
  CI (99.9%): [5.868, 10.428] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.004 ms/op
Iteration   1: 3.016 ±(99.9%) 0.011 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.007 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (2.978, 3.007, 3.025), stdev = 0.025
  CI (99.9%): [2.554, 3.459] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.977 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.004 ms/op
Iteration   1: 2.872 ±(99.9%) 0.002 ms/op
Iteration   2: 2.838 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.861 ±(99.9%) 0.370 ms/op [Average]
  (min, avg, max) = (2.838, 2.861, 2.874), stdev = 0.020
  CI (99.9%): [2.491, 3.231] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.004 ms/op
Iteration   1: 3.040 ±(99.9%) 0.004 ms/op
Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
Iteration   3: 3.022 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.010, 3.024, 3.040), stdev = 0.015
  CI (99.9%): [2.748, 3.300] (assumes normal distribution)


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
# Warmup Iteration   1: 5.226 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.013 ms/op
Iteration   1: 3.941 ±(99.9%) 0.008 ms/op
Iteration   2: 3.875 ±(99.9%) 0.017 ms/op
Iteration   3: 3.889 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.875, 3.902, 3.941), stdev = 0.035
  CI (99.9%): [3.271, 4.532] (assumes normal distribution)


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  9.896 ms/op
                 createUser·p0.9999: 12.778 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.363 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.975 ms/op
                 createUser·p0.9999: 15.493 ms/op
                 createUser·p1.00:   15.860 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.846 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.728 ms/op
                 createUser·p0.9999: 23.054 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316715
  mean =      3.031 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24337 
    [ 2.500,  5.000) = 290781 
    [ 5.000,  7.500) = 1136 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.463 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.972 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
Iteration   1: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.176 ms/op
                 existUser·p0.9999: 22.110 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   2: 2.930 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   3.975 ms/op
                 existUser·p0.999:  6.054 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   3: 2.885 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  8.963 ms/op
                 existUser·p0.9999: 15.511 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331446
  mean =      2.896 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42256 
    [ 2.500,  5.000) = 288019 
    [ 5.000,  7.500) = 854 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     15.890 ms/op
     p(99.9990) =     22.425 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 4.252 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.444 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.199 ms/op
                 getUser·p0.9999: 16.564 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 26.722 ms/op
                 getUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315289
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22059 
    [ 2.500,  5.000) = 291681 
    [ 5.000,  7.500) = 1284 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      6.963 ms/op
     p(99.9900) =     25.179 ms/op
     p(99.9990) =     26.832 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 5.357 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.354 ms/op
                 listUser·p0.9999: 18.576 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 18.734 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.676 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.195 ms/op
                 listUser·p0.9999: 18.022 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245202
  mean =      3.914 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2492 
    [ 2.500,  5.000) = 222302 
    [ 5.000,  7.500) = 19414 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     18.595 ms/op
     p(99.9990) =     20.989 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.675 ± 3.907  ops/ms
ClientGrpc.existUser                       thrpt       3  11.095 ± 1.227  ops/ms
ClientGrpc.getUser                         thrpt       3  10.667 ± 0.655  ops/ms
ClientGrpc.listUser                        thrpt       3   8.148 ± 2.280  ops/ms
ClientGrpc.createUser                       avgt       3   3.007 ± 0.453   ms/op
ClientGrpc.existUser                        avgt       3   2.861 ± 0.370   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.276   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 0.631   ms/op
ClientGrpc.createUser                     sample  316715   3.031 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.539           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.463           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.037           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  331446   2.896 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.683           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.610           ms/op
ClientGrpc.getUser                        sample  315289   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.564           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.963           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.179           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.935           ms/op
ClientGrpc.listUser                       sample  245202   3.914 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.676           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.549           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.595           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.004           ms/op
