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
# Warmup Iteration   1: 4.644 ops/ms
# Warmup Iteration   2: 9.207 ops/ms
# Warmup Iteration   3: 10.509 ops/ms
Iteration   1: 10.672 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.640 ±(99.9%) 0.883 ops/ms [Average]
  (min, avg, max) = (10.585, 10.640, 10.672), stdev = 0.048
  CI (99.9%): [9.757, 11.523] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.734 ops/ms
# Warmup Iteration   2: 10.928 ops/ms
# Warmup Iteration   3: 11.254 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.868 ops/ms
Iteration   3: 10.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.749 ±(99.9%) 3.436 ops/ms [Average]
  (min, avg, max) = (10.532, 10.749, 10.868), stdev = 0.188
  CI (99.9%): [7.313, 14.186] (assumes normal distribution)


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
# Warmup Iteration   1: 7.121 ops/ms
# Warmup Iteration   2: 9.978 ops/ms
# Warmup Iteration   3: 10.423 ops/ms
Iteration   1: 10.482 ops/ms
Iteration   2: 10.280 ops/ms
Iteration   3: 10.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.400 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (10.280, 10.400, 10.482), stdev = 0.106
  CI (99.9%): [8.459, 12.341] (assumes normal distribution)


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
# Warmup Iteration   1: 5.466 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.000 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.118 ±(99.9%) 1.543 ops/ms [Average]
  (min, avg, max) = (8.036, 8.118, 8.205), stdev = 0.085
  CI (99.9%): [6.575, 9.661] (assumes normal distribution)


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.003 ms/op
Iteration   1: 3.052 ±(99.9%) 0.005 ms/op
Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
Iteration   3: 3.020 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.543 ms/op [Average]
  (min, avg, max) = (2.992, 3.021, 3.052), stdev = 0.030
  CI (99.9%): [2.478, 3.564] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.059 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.002 ms/op
Iteration   1: 2.905 ±(99.9%) 0.002 ms/op
Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.939 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.905, 2.939, 2.974), stdev = 0.034
  CI (99.9%): [2.314, 3.563] (assumes normal distribution)


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.003 ms/op
Iteration   1: 3.054 ±(99.9%) 0.003 ms/op
Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
Iteration   3: 3.017 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (3.007, 3.026, 3.054), stdev = 0.024
  CI (99.9%): [2.580, 3.472] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.363 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.022 ms/op
Iteration   1: 3.957 ±(99.9%) 0.017 ms/op
Iteration   2: 3.906 ±(99.9%) 0.019 ms/op
Iteration   3: 3.888 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.917 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.888, 3.917, 3.957), stdev = 0.036
  CI (99.9%): [3.260, 4.575] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.547 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.865 ms/op
                 createUser·p0.9999: 18.994 ms/op
                 createUser·p1.00:   19.268 ms/op

Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.467 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.287 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   3: 2.987 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.301 ms/op
                 createUser·p0.9999: 25.054 ms/op
                 createUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320054
  mean =      2.999 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25253 
    [ 2.500,  5.000) = 293120 
    [ 5.000,  7.500) = 1121 
    [ 7.500, 10.000) = 303 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     25.428 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 3.763 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.932 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.588 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  6.724 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   12.009 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.030 ms/op
                 existUser·p0.999:  8.327 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.386 ms/op
                 existUser·p0.999:  10.125 ms/op
                 existUser·p0.9999: 16.742 ms/op
                 existUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321101
  mean =      2.988 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28086 
    [ 2.500,  5.000) = 291129 
    [ 5.000,  7.500) = 1385 
    [ 7.500, 10.000) = 284 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.438 ms/op
     p(99.9900) =     21.572 ms/op
     p(99.9990) =     22.629 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 4.296 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   4.891 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 14.119 ms/op
                 getUser·p1.00:   14.287 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  9.217 ms/op
                 getUser·p0.9999: 16.392 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 3.098 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  9.314 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308157
  mean =      3.112 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27009 
    [ 2.500,  5.000) = 278291 
    [ 5.000,  7.500) = 2248 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =      8.730 ms/op
     p(99.9900) =     23.665 ms/op
     p(99.9990) =     27.558 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 5.119 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.177 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.011 ms/op
Iteration   1: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   7.145 ms/op
                 listUser·p0.999:  13.029 ms/op
                 listUser·p0.9999: 15.921 ms/op
                 listUser·p1.00:   17.236 ms/op

Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.133 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 17.761 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 4.066 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.490 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 22.782 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239477
  mean =      4.008 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4356 
    [ 2.500,  5.000) = 208875 
    [ 5.000,  7.500) = 24526 
    [ 7.500, 10.000) = 1170 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     14.778 ms/op
     p(99.9900) =     21.629 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.640 ± 0.883  ops/ms
ClientGrpc.existUser                       thrpt       3  10.749 ± 3.436  ops/ms
ClientGrpc.getUser                         thrpt       3  10.400 ± 1.941  ops/ms
ClientGrpc.listUser                        thrpt       3   8.118 ± 1.543  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.543   ms/op
ClientGrpc.existUser                        avgt       3   2.939 ± 0.624   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.446   ms/op
ClientGrpc.listUser                         avgt       3   3.917 ± 0.658   ms/op
ClientGrpc.createUser                     sample  320054   2.999 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.467           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.429           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.526           ms/op
ClientGrpc.existUser                      sample  321101   2.988 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.588           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.514           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.572           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  308157   3.112 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.643           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.006           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.923           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.665           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.623           ms/op
ClientGrpc.listUser                       sample  239477   4.008 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.490           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.193           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.778           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.629           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.855           ms/op
