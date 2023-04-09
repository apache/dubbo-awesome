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
# Warmup Iteration   1: 3.281 ops/ms
# Warmup Iteration   2: 6.627 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.517 ops/ms
Iteration   2: 8.171 ops/ms
Iteration   3: 8.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.418 ±(99.9%) 3.923 ops/ms [Average]
  (min, avg, max) = (8.171, 8.418, 8.565), stdev = 0.215
  CI (99.9%): [4.495, 12.341] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.003 ops/ms
# Warmup Iteration   2: 8.454 ops/ms
# Warmup Iteration   3: 8.763 ops/ms
Iteration   1: 8.854 ops/ms
Iteration   2: 8.988 ops/ms
Iteration   3: 9.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.973 ±(99.9%) 2.065 ops/ms [Average]
  (min, avg, max) = (8.854, 8.973, 9.079), stdev = 0.113
  CI (99.9%): [6.908, 11.039] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.624 ops/ms
# Warmup Iteration   2: 8.270 ops/ms
# Warmup Iteration   3: 8.785 ops/ms
Iteration   1: 8.536 ops/ms
Iteration   2: 8.337 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.433 ±(99.9%) 1.818 ops/ms [Average]
  (min, avg, max) = (8.337, 8.433, 8.536), stdev = 0.100
  CI (99.9%): [6.615, 10.251] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.667 ops/ms
# Warmup Iteration   2: 6.249 ops/ms
# Warmup Iteration   3: 6.609 ops/ms
Iteration   1: 6.857 ops/ms
Iteration   2: 6.609 ops/ms
Iteration   3: 6.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.657 ±(99.9%) 3.302 ops/ms [Average]
  (min, avg, max) = (6.504, 6.657, 6.857), stdev = 0.181
  CI (99.9%): [3.355, 9.959] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.349 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.006 ms/op
Iteration   1: 3.805 ±(99.9%) 0.004 ms/op
Iteration   2: 3.572 ±(99.9%) 0.002 ms/op
Iteration   3: 3.650 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.676 ±(99.9%) 2.168 ms/op [Average]
  (min, avg, max) = (3.572, 3.676, 3.805), stdev = 0.119
  CI (99.9%): [1.508, 5.843] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.843 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.005 ms/op
Iteration   1: 3.517 ±(99.9%) 0.004 ms/op
Iteration   2: 3.512 ±(99.9%) 0.004 ms/op
Iteration   3: 3.474 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.501 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.474, 3.501, 3.517), stdev = 0.024
  CI (99.9%): [3.066, 3.936] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.498 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.004 ms/op
Iteration   1: 3.716 ±(99.9%) 0.004 ms/op
Iteration   2: 3.841 ±(99.9%) 0.002 ms/op
Iteration   3: 3.778 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.778 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.716, 3.778, 3.841), stdev = 0.062
  CI (99.9%): [2.643, 4.913] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.981 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.299 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.036 ±(99.9%) 0.016 ms/op
Iteration   1: 4.798 ±(99.9%) 0.019 ms/op
Iteration   2: 4.899 ±(99.9%) 0.011 ms/op
Iteration   3: 5.036 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.911 ±(99.9%) 2.172 ms/op [Average]
  (min, avg, max) = (4.798, 4.911, 5.036), stdev = 0.119
  CI (99.9%): [2.739, 7.083] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.368 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.964 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.010 ms/op
Iteration   1: 3.696 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   14.582 ms/op

Iteration   2: 3.809 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  13.632 ms/op
                 createUser·p0.9999: 20.002 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   3: 3.703 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.815 ms/op
                 createUser·p0.999:  9.365 ms/op
                 createUser·p0.9999: 20.033 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257056
  mean =      3.735 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3926 
    [ 2.500,  5.000) = 242779 
    [ 5.000,  7.500) = 8775 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     19.802 ms/op
     p(99.9990) =     20.429 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.086 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.009 ms/op
Iteration   1: 3.555 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 15.794 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   2: 3.568 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.697 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  8.786 ms/op
                 existUser·p0.9999: 16.450 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   3: 3.524 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.827 ms/op
                 existUser·p0.999:  10.146 ms/op
                 existUser·p0.9999: 18.183 ms/op
                 existUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270583
  mean =      3.549 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18443 
    [ 2.500,  5.000) = 241536 
    [ 5.000,  7.500) = 8975 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     17.431 ms/op
     p(99.9990) =     18.618 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.246 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.010 ms/op
Iteration   1: 3.654 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  9.469 ms/op
                 getUser·p0.9999: 16.163 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 3.789 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 19.417 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.818 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.505 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.719 ms/op
                 getUser·p0.95:   5.267 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  12.707 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255725
  mean =      3.752 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 173 
    [ 1.250,  2.500) = 8943 
    [ 2.500,  3.750) = 140162 
    [ 3.750,  5.000) = 92784 
    [ 5.000,  6.250) = 9476 
    [ 6.250,  7.500) = 2114 
    [ 7.500,  8.750) = 1361 
    [ 8.750, 10.000) = 389 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.708 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 5.806 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.323 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.007 ±(99.9%) 0.017 ms/op
Iteration   1: 4.893 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.340 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  15.946 ms/op
                 listUser·p0.9999: 23.425 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   2: 4.839 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   6.914 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 22.235 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.804 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.111 ms/op
                 listUser·p0.99:   9.044 ms/op
                 listUser·p0.999:  27.241 ms/op
                 listUser·p0.9999: 32.103 ms/op
                 listUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197998
  mean =      4.845 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 343 
    [ 2.500,  5.000) = 141598 
    [ 5.000,  7.500) = 48701 
    [ 7.500, 10.000) = 6130 
    [10.000, 12.500) = 768 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      7.127 ms/op
     p(99.0000) =      9.175 ms/op
     p(99.9000) =     18.711 ms/op
     p(99.9900) =     31.654 ms/op
     p(99.9990) =     32.703 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.418 ± 3.923  ops/ms
ClientGrpc.existUser                       thrpt       3   8.973 ± 2.065  ops/ms
ClientGrpc.getUser                         thrpt       3   8.433 ± 1.818  ops/ms
ClientGrpc.listUser                        thrpt       3   6.657 ± 3.302  ops/ms
ClientGrpc.createUser                       avgt       3   3.676 ± 2.168   ms/op
ClientGrpc.existUser                        avgt       3   3.501 ± 0.435   ms/op
ClientGrpc.getUser                          avgt       3   3.778 ± 1.135   ms/op
ClientGrpc.listUser                         avgt       3   4.911 ± 2.172   ms/op
ClientGrpc.createUser                     sample  257056   3.735 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.948           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.832           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.503           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.802           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  270583   3.549 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.697           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.849           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.503           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.431           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.593           ms/op
ClientGrpc.getUser                        sample  255725   3.752 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.505           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.160           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.961           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.235           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.792           ms/op
ClientGrpc.listUser                       sample  197998   4.845 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.127           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.175           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.711           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.654           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.735           ms/op
