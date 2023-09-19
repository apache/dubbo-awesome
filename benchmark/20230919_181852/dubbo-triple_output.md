# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.667 ops/ms
# Warmup Iteration   2: 5.425 ops/ms
# Warmup Iteration   3: 8.437 ops/ms
Iteration   1: 8.633 ops/ms
Iteration   2: 9.225 ops/ms
Iteration   3: 9.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.019 ±(99.9%) 6.110 ops/ms [Average]
  (min, avg, max) = (8.633, 9.019, 9.225), stdev = 0.335
  CI (99.9%): [2.909, 15.129] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.890 ops/ms
# Warmup Iteration   2: 8.633 ops/ms
# Warmup Iteration   3: 9.501 ops/ms
Iteration   1: 9.445 ops/ms
Iteration   2: 9.641 ops/ms
Iteration   3: 9.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.578 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (9.445, 9.578, 9.648), stdev = 0.115
  CI (99.9%): [7.473, 11.683] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.411 ops/ms
# Warmup Iteration   2: 8.255 ops/ms
# Warmup Iteration   3: 8.766 ops/ms
Iteration   1: 8.884 ops/ms
Iteration   2: 9.177 ops/ms
Iteration   3: 9.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.036 ±(99.9%) 2.680 ops/ms [Average]
  (min, avg, max) = (8.884, 9.036, 9.177), stdev = 0.147
  CI (99.9%): [6.356, 11.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.645 ops/ms
# Warmup Iteration   2: 7.027 ops/ms
# Warmup Iteration   3: 7.534 ops/ms
Iteration   1: 7.490 ops/ms
Iteration   2: 7.661 ops/ms
Iteration   3: 7.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.574 ±(99.9%) 1.562 ops/ms [Average]
  (min, avg, max) = (7.490, 7.574, 7.661), stdev = 0.086
  CI (99.9%): [6.011, 9.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.234 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.006 ms/op
Iteration   1: 3.505 ±(99.9%) 0.004 ms/op
Iteration   2: 3.487 ±(99.9%) 0.003 ms/op
Iteration   3: 3.547 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.513 ±(99.9%) 0.557 ms/op [Average]
  (min, avg, max) = (3.487, 3.513, 3.547), stdev = 0.031
  CI (99.9%): [2.956, 4.070] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.582 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.004 ms/op
Iteration   1: 3.426 ±(99.9%) 0.007 ms/op
Iteration   2: 3.379 ±(99.9%) 0.008 ms/op
Iteration   3: 3.386 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.397 ±(99.9%) 0.461 ms/op [Average]
  (min, avg, max) = (3.379, 3.397, 3.426), stdev = 0.025
  CI (99.9%): [2.937, 3.858] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.514 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.841 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.004 ms/op
Iteration   1: 3.565 ±(99.9%) 0.004 ms/op
Iteration   2: 3.474 ±(99.9%) 0.005 ms/op
Iteration   3: 3.404 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.481 ±(99.9%) 1.472 ms/op [Average]
  (min, avg, max) = (3.404, 3.481, 3.565), stdev = 0.081
  CI (99.9%): [2.010, 4.953] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.970 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.006 ms/op
Iteration   1: 4.356 ±(99.9%) 0.008 ms/op
Iteration   2: 4.146 ±(99.9%) 0.010 ms/op
Iteration   3: 4.195 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.233 ±(99.9%) 2.004 ms/op [Average]
  (min, avg, max) = (4.146, 4.233, 4.356), stdev = 0.110
  CI (99.9%): [2.228, 6.237] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.625 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.748 ±(99.9%) 0.014 ms/op
Iteration   1: 3.531 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.185 ms/op
                 createUser·p0.999:  22.980 ms/op
                 createUser·p0.9999: 25.779 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 3.485 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  24.117 ms/op
                 createUser·p0.9999: 27.644 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   3: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.753 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 28.745 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273252
  mean =      3.514 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3666 
    [ 2.500,  5.000) = 263626 
    [ 5.000,  7.500) = 4781 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 132 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     22.675 ms/op
     p(99.9900) =     27.931 ms/op
     p(99.9990) =     30.024 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.721 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.009 ms/op
Iteration   1: 3.493 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.708 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.818 ms/op
                 existUser·p0.999:  21.987 ms/op
                 existUser·p0.9999: 24.633 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 3.429 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   6.383 ms/op
                 existUser·p0.999:  24.379 ms/op
                 existUser·p0.9999: 29.677 ms/op
                 existUser·p1.00:   35.914 ms/op

Iteration   3: 3.584 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  24.936 ms/op
                 existUser·p0.9999: 29.912 ms/op
                 existUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 274079
  mean =      3.501 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5987 
    [ 2.500,  5.000) = 260628 
    [ 5.000,  7.500) = 5969 
    [ 7.500, 10.000) = 933 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 132 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     22.673 ms/op
     p(99.9900) =     29.393 ms/op
     p(99.9990) =     31.102 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.165 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.672 ±(99.9%) 0.011 ms/op
Iteration   1: 3.645 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   7.291 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 23.731 ms/op
                 getUser·p1.00:   30.769 ms/op

Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  21.101 ms/op
                 getUser·p0.9999: 23.593 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   3: 3.571 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  23.735 ms/op
                 getUser·p0.9999: 26.774 ms/op
                 getUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 268167
  mean =      3.576 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4600 
    [ 2.500,  5.000) = 254023 
    [ 5.000,  7.500) = 7879 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 142 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     20.409 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     27.972 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.648 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.015 ms/op
Iteration   1: 4.274 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.677 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.323 ms/op
                 listUser·p0.99:   8.200 ms/op
                 listUser·p0.999:  22.550 ms/op
                 listUser·p0.9999: 25.052 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   2: 4.252 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  16.974 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.196 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.023 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 20.525 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226296
  mean =      4.240 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 213724 
    [ 5.000,  7.500) = 10262 
    [ 7.500, 10.000) = 1487 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.677 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     17.564 ms/op
     p(99.9900) =     24.457 ms/op
     p(99.9990) =     25.271 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.019 ± 6.110  ops/ms
ClientPb.existUser                       thrpt       3   9.578 ± 2.105  ops/ms
ClientPb.getUser                         thrpt       3   9.036 ± 2.680  ops/ms
ClientPb.listUser                        thrpt       3   7.574 ± 1.562  ops/ms
ClientPb.createUser                       avgt       3   3.513 ± 0.557   ms/op
ClientPb.existUser                        avgt       3   3.397 ± 0.461   ms/op
ClientPb.getUser                          avgt       3   3.481 ± 1.472   ms/op
ClientPb.listUser                         avgt       3   4.233 ± 2.004   ms/op
ClientPb.createUser                     sample  273252   3.514 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.454           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.054           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.675           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  274079   3.501 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.373           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.673           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.393           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914           ms/op
ClientPb.getUser                        sample  268167   3.576 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.980           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.409           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.887           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  226296   4.240 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.677           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.512           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.564           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.457           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.854           ms/op
