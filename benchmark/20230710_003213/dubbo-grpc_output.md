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
# Warmup Iteration   1: 2.300 ops/ms
# Warmup Iteration   2: 5.594 ops/ms
# Warmup Iteration   3: 7.103 ops/ms
Iteration   1: 7.522 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.586 ±(99.9%) 1.794 ops/ms [Average]
  (min, avg, max) = (7.522, 7.586, 7.700), stdev = 0.098
  CI (99.9%): [5.792, 9.380] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ops/ms
# Warmup Iteration   2: 7.311 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 8.055 ops/ms
Iteration   2: 7.740 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.932 ±(99.9%) 3.069 ops/ms [Average]
  (min, avg, max) = (7.740, 7.932, 8.055), stdev = 0.168
  CI (99.9%): [4.863, 11.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 7.179 ops/ms
Iteration   1: 7.570 ops/ms
Iteration   2: 7.371 ops/ms
Iteration   3: 7.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.455 ±(99.9%) 1.879 ops/ms [Average]
  (min, avg, max) = (7.371, 7.455, 7.570), stdev = 0.103
  CI (99.9%): [5.577, 9.334] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.340 ops/ms
# Warmup Iteration   2: 5.378 ops/ms
# Warmup Iteration   3: 5.453 ops/ms
Iteration   1: 5.850 ops/ms
Iteration   2: 5.835 ops/ms
Iteration   3: 5.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.816 ±(99.9%) 0.849 ops/ms [Average]
  (min, avg, max) = (5.763, 5.816, 5.850), stdev = 0.047
  CI (99.9%): [4.968, 6.665] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.665 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.300 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.339 ±(99.9%) 0.004 ms/op
Iteration   1: 4.206 ±(99.9%) 0.002 ms/op
Iteration   2: 4.176 ±(99.9%) 0.003 ms/op
Iteration   3: 4.097 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.160 ±(99.9%) 1.028 ms/op [Average]
  (min, avg, max) = (4.097, 4.160, 4.206), stdev = 0.056
  CI (99.9%): [3.132, 5.188] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.010 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.025 ms/op
Iteration   1: 4.012 ±(99.9%) 0.003 ms/op
Iteration   2: 4.087 ±(99.9%) 0.002 ms/op
Iteration   3: 4.098 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.066 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (4.012, 4.066, 4.098), stdev = 0.047
  CI (99.9%): [3.211, 4.921] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.636 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.004 ms/op
Iteration   1: 4.415 ±(99.9%) 0.004 ms/op
Iteration   2: 4.351 ±(99.9%) 0.005 ms/op
Iteration   3: 4.236 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.334 ±(99.9%) 1.658 ms/op [Average]
  (min, avg, max) = (4.236, 4.334, 4.415), stdev = 0.091
  CI (99.9%): [2.676, 5.992] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.468 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 6.031 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.016 ms/op
Iteration   1: 5.667 ±(99.9%) 0.023 ms/op
Iteration   2: 5.449 ±(99.9%) 0.020 ms/op
Iteration   3: 5.569 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.562 ±(99.9%) 1.989 ms/op [Average]
  (min, avg, max) = (5.449, 5.562, 5.667), stdev = 0.109
  CI (99.9%): [3.573, 7.550] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.796 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.365 ±(99.9%) 0.015 ms/op
Iteration   1: 4.275 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   4.149 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   7.238 ms/op
                 createUser·p0.999:  10.961 ms/op
                 createUser·p0.9999: 18.416 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 4.196 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.358 ms/op
                 createUser·p0.95:   5.833 ms/op
                 createUser·p0.99:   7.127 ms/op
                 createUser·p0.999:  10.093 ms/op
                 createUser·p0.9999: 17.764 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 4.125 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  13.163 ms/op
                 createUser·p0.9999: 22.806 ms/op
                 createUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228697
  mean =      4.198 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4184 
    [ 2.500,  5.000) = 186966 
    [ 5.000,  7.500) = 35514 
    [ 7.500, 10.000) = 1631 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     20.120 ms/op
     p(99.9990) =     23.405 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.972 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.012 ms/op
Iteration   1: 4.173 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   4.022 ms/op
                 existUser·p0.90:   5.235 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 18.296 ms/op
                 existUser·p1.00:   19.005 ms/op

Iteration   2: 3.986 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  12.660 ms/op
                 existUser·p0.9999: 18.871 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   5.014 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  10.695 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238581
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5610 
    [ 2.500,  5.000) = 206390 
    [ 5.000,  7.500) = 24373 
    [ 7.500, 10.000) = 1828 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     21.088 ms/op
     p(99.9990) =     22.728 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.475 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.628 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.013 ms/op
Iteration   1: 4.249 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.848 ms/op
                 getUser·p0.999:  12.894 ms/op
                 getUser·p0.9999: 19.938 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   2: 4.206 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   5.276 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  11.332 ms/op
                 getUser·p0.9999: 16.502 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   3: 4.181 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  11.526 ms/op
                 getUser·p0.9999: 23.342 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227858
  mean =      4.212 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5364 
    [ 2.500,  5.000) = 187253 
    [ 5.000,  7.500) = 32832 
    [ 7.500, 10.000) = 1888 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     12.045 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     23.542 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 8.675 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 5.911 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.515 ±(99.9%) 0.021 ms/op
Iteration   1: 5.484 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.077 ms/op
                 listUser·p0.99:   10.650 ms/op
                 listUser·p0.999:  16.312 ms/op
                 listUser·p0.9999: 26.220 ms/op
                 listUser·p1.00:   26.673 ms/op

Iteration   2: 5.582 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  19.048 ms/op
                 listUser·p0.9999: 22.507 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 5.737 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   5.390 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.141 ms/op
                 listUser·p0.999:  27.631 ms/op
                 listUser·p0.9999: 31.559 ms/op
                 listUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 171543
  mean =      5.599 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 65693 
    [ 5.000,  7.500) = 89131 
    [ 7.500, 10.000) = 13580 
    [10.000, 12.500) = 2228 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.447 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     20.331 ms/op
     p(99.9900) =     30.552 ms/op
     p(99.9990) =     31.869 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.586 ± 1.794  ops/ms
ClientGrpc.existUser                       thrpt       3   7.932 ± 3.069  ops/ms
ClientGrpc.getUser                         thrpt       3   7.455 ± 1.879  ops/ms
ClientGrpc.listUser                        thrpt       3   5.816 ± 0.849  ops/ms
ClientGrpc.createUser                       avgt       3   4.160 ± 1.028   ms/op
ClientGrpc.existUser                        avgt       3   4.066 ± 0.855   ms/op
ClientGrpc.getUser                          avgt       3   4.334 ± 1.658   ms/op
ClientGrpc.listUser                         avgt       3   5.562 ± 1.989   ms/op
ClientGrpc.createUser                     sample  228697   4.198 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.724           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.374           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.356           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.026           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.120           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  238581   4.024 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.950           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.079           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.595           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.365           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.633           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.088           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.872           ms/op
ClientGrpc.getUser                        sample  227858   4.212 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.678           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.825           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.045           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.709           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  171543   5.599 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.253           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.447           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.879           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.331           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.552           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.916           ms/op
