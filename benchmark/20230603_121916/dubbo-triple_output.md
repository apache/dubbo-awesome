# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.197 ops/ms
# Warmup Iteration   2: 5.183 ops/ms
# Warmup Iteration   3: 8.401 ops/ms
Iteration   1: 9.105 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.253 ±(99.9%) 2.342 ops/ms [Average]
  (min, avg, max) = (9.105, 9.253, 9.342), stdev = 0.128
  CI (99.9%): [6.911, 11.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.022 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.141 ops/ms
Iteration   1: 9.529 ops/ms
Iteration   2: 10.023 ops/ms
Iteration   3: 9.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.752 ±(99.9%) 4.563 ops/ms [Average]
  (min, avg, max) = (9.529, 9.752, 10.023), stdev = 0.250
  CI (99.9%): [5.189, 14.315] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.304 ops/ms
# Warmup Iteration   2: 8.584 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.018 ops/ms
Iteration   2: 9.497 ops/ms
Iteration   3: 9.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.286 ±(99.9%) 4.461 ops/ms [Average]
  (min, avg, max) = (9.018, 9.286, 9.497), stdev = 0.245
  CI (99.9%): [4.825, 13.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.409 ops/ms
# Warmup Iteration   2: 6.510 ops/ms
# Warmup Iteration   3: 7.700 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 8.057 ops/ms
Iteration   3: 7.869 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.966 ±(99.9%) 1.719 ops/ms [Average]
  (min, avg, max) = (7.869, 7.966, 8.057), stdev = 0.094
  CI (99.9%): [6.247, 9.686] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.973 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.002 ms/op
Iteration   1: 3.579 ±(99.9%) 0.008 ms/op
Iteration   2: 3.611 ±(99.9%) 0.006 ms/op
Iteration   3: 3.428 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.539 ±(99.9%) 1.783 ms/op [Average]
  (min, avg, max) = (3.428, 3.539, 3.611), stdev = 0.098
  CI (99.9%): [1.756, 5.322] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.199 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.597 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.007 ms/op
Iteration   1: 3.413 ±(99.9%) 0.004 ms/op
Iteration   2: 3.354 ±(99.9%) 0.008 ms/op
Iteration   3: 3.453 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.407 ±(99.9%) 0.910 ms/op [Average]
  (min, avg, max) = (3.354, 3.407, 3.453), stdev = 0.050
  CI (99.9%): [2.497, 4.317] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.825 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.008 ms/op
Iteration   1: 3.469 ±(99.9%) 0.005 ms/op
Iteration   2: 3.486 ±(99.9%) 0.006 ms/op
Iteration   3: 3.606 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.520 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.469, 3.520, 3.606), stdev = 0.075
  CI (99.9%): [2.158, 4.883] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.181 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.976 ±(99.9%) 0.009 ms/op
Iteration   2: 3.987 ±(99.9%) 0.012 ms/op
Iteration   3: 3.987 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.983 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.976, 3.983, 3.987), stdev = 0.006
  CI (99.9%): [3.866, 4.101] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.371 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.011 ms/op
Iteration   1: 3.628 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.340 ms/op
                 createUser·p0.999:  20.054 ms/op
                 createUser·p0.9999: 22.785 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   2: 3.477 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  22.184 ms/op
                 createUser·p0.9999: 26.399 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   3: 3.411 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.103 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  17.343 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273804
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6333 
    [ 2.500,  5.000) = 257703 
    [ 5.000,  7.500) = 8579 
    [ 7.500, 10.000) = 794 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.316 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     27.077 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.404 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  10.616 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  20.933 ms/op
                 existUser·p0.9999: 23.252 ms/op
                 existUser·p1.00:   24.248 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.998 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  21.234 ms/op
                 existUser·p0.9999: 25.407 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282354
  mean =      3.397 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9969 
    [ 2.500,  5.000) = 266012 
    [ 5.000,  7.500) = 5359 
    [ 7.500, 10.000) = 570 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     14.329 ms/op
     p(99.9900) =     24.445 ms/op
     p(99.9990) =     25.767 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.003 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.651 ±(99.9%) 0.013 ms/op
Iteration   1: 3.534 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  17.170 ms/op
                 getUser·p0.9999: 22.248 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  21.467 ms/op
                 getUser·p0.9999: 26.051 ms/op
                 getUser·p1.00:   26.739 ms/op

Iteration   3: 3.513 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.864 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 27.227 ms/op
                 getUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275501
  mean =      3.482 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7837 
    [ 2.500,  5.000) = 260719 
    [ 5.000,  7.500) = 5390 
    [ 7.500, 10.000) = 1094 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 74 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     17.220 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     28.409 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.965 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.014 ms/op
Iteration   1: 4.074 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.952 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  20.382 ms/op
                 listUser·p0.9999: 26.256 ms/op
                 listUser·p1.00:   26.509 ms/op

Iteration   2: 3.937 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  15.773 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 4.198 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 18.541 ms/op
                 listUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235956
  mean =      4.067 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 227936 
    [ 5.000,  7.500) = 5814 
    [ 7.500, 10.000) = 1355 
    [10.000, 12.500) = 342 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 239 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.952 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     25.114 ms/op
     p(99.9990) =     26.432 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.253 ± 2.342  ops/ms
ClientPb.existUser                       thrpt       3   9.752 ± 4.563  ops/ms
ClientPb.getUser                         thrpt       3   9.286 ± 4.461  ops/ms
ClientPb.listUser                        thrpt       3   7.966 ± 1.719  ops/ms
ClientPb.createUser                       avgt       3   3.539 ± 1.783   ms/op
ClientPb.existUser                        avgt       3   3.407 ± 0.910   ms/op
ClientPb.getUser                          avgt       3   3.520 ± 1.363   ms/op
ClientPb.listUser                         avgt       3   3.983 ± 0.118   ms/op
ClientPb.createUser                     sample  273804   3.503 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.157           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.316           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.596           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.231           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.230           ms/op
ClientPb.existUser                      sample  282354   3.397 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.106           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.329           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.445           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.854           ms/op
ClientPb.getUser                        sample  275501   3.482 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.220           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.542           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.606           ms/op
ClientPb.listUser                       sample  235956   4.067 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.952           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.348           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.114           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.509           ms/op
