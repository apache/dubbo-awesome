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
# Warmup Iteration   1: 1.822 ops/ms
# Warmup Iteration   2: 4.795 ops/ms
# Warmup Iteration   3: 8.455 ops/ms
Iteration   1: 9.201 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.350 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (9.201, 9.350, 9.475), stdev = 0.138
  CI (99.9%): [6.824, 11.877] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.396 ops/ms
# Warmup Iteration   2: 8.444 ops/ms
# Warmup Iteration   3: 9.709 ops/ms
Iteration   1: 9.928 ops/ms
Iteration   2: 9.828 ops/ms
Iteration   3: 9.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.815 ±(99.9%) 2.197 ops/ms [Average]
  (min, avg, max) = (9.688, 9.815, 9.928), stdev = 0.120
  CI (99.9%): [7.618, 12.012] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.673 ops/ms
# Warmup Iteration   2: 8.490 ops/ms
# Warmup Iteration   3: 8.796 ops/ms
Iteration   1: 9.199 ops/ms
Iteration   2: 9.321 ops/ms
Iteration   3: 9.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.243 ±(99.9%) 1.232 ops/ms [Average]
  (min, avg, max) = (9.199, 9.243, 9.321), stdev = 0.068
  CI (99.9%): [8.011, 10.475] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.697 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 7.886 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.061 ops/ms
Iteration   3: 8.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.070 ±(99.9%) 0.714 ops/ms [Average]
  (min, avg, max) = (8.036, 8.070, 8.113), stdev = 0.039
  CI (99.9%): [7.356, 8.784] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.929 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.009 ms/op
Iteration   1: 3.462 ±(99.9%) 0.005 ms/op
Iteration   2: 3.349 ±(99.9%) 0.004 ms/op
Iteration   3: 3.345 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.385 ±(99.9%) 1.212 ms/op [Average]
  (min, avg, max) = (3.345, 3.385, 3.462), stdev = 0.066
  CI (99.9%): [2.173, 4.597] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.689 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.007 ms/op
Iteration   1: 3.400 ±(99.9%) 0.004 ms/op
Iteration   2: 3.331 ±(99.9%) 0.008 ms/op
Iteration   3: 3.425 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.386 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.331, 3.386, 3.425), stdev = 0.049
  CI (99.9%): [2.497, 4.274] (assumes normal distribution)


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
# Warmup Iteration   1: 10.576 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.006 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
Iteration   2: 3.381 ±(99.9%) 0.006 ms/op
Iteration   3: 3.358 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.381 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.358, 3.381, 3.403), stdev = 0.022
  CI (99.9%): [2.971, 3.791] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.434 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.539 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.012 ms/op
Iteration   1: 4.042 ±(99.9%) 0.010 ms/op
Iteration   2: 4.013 ±(99.9%) 0.013 ms/op
Iteration   3: 3.927 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.994 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.927, 3.994, 4.042), stdev = 0.060
  CI (99.9%): [2.906, 5.081] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.454 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.011 ms/op
Iteration   1: 3.478 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.804 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  21.729 ms/op
                 createUser·p0.9999: 24.045 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   2: 3.450 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 29.745 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  21.986 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276130
  mean =      3.472 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8375 
    [ 2.500,  5.000) = 261430 
    [ 5.000,  7.500) = 5058 
    [ 7.500, 10.000) = 657 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.383 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     21.950 ms/op
     p(99.9900) =     28.881 ms/op
     p(99.9990) =     30.545 ms/op
     p(99.9999) =     30.835 ms/op
    p(100.0000) =     30.835 ms/op


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
# Warmup Iteration   1: 8.410 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.653 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.947 ms/op
                 existUser·p0.999:  21.714 ms/op
                 existUser·p0.9999: 24.379 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   2: 3.374 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   5.156 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 27.171 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   3: 3.344 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  24.949 ms/op
                 existUser·p0.9999: 34.697 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284483
  mean =      3.373 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12145 
    [ 2.500,  5.000) = 266671 
    [ 5.000,  7.500) = 5020 
    [ 7.500, 10.000) = 269 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     32.578 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 10.091 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.012 ms/op
Iteration   1: 3.495 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  22.068 ms/op
                 getUser·p0.9999: 26.706 ms/op
                 getUser·p1.00:   28.803 ms/op

Iteration   2: 3.469 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.788 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.002 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  24.817 ms/op
                 getUser·p0.9999: 29.156 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  18.236 ms/op
                 getUser·p0.9999: 28.574 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280038
  mean =      3.426 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10147 
    [ 2.500,  5.000) = 261874 
    [ 5.000,  7.500) = 6781 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 94 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.431 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     28.869 ms/op
     p(99.9990) =     29.426 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 11.391 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.469 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.013 ms/op
Iteration   1: 4.215 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.901 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 25.927 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 4.008 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 17.433 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  16.362 ms/op
                 listUser·p0.9999: 24.625 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237411
  mean =      4.042 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 227687 
    [ 5.000,  7.500) = 7109 
    [ 7.500, 10.000) = 1890 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.681 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     24.855 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.350 ± 2.527  ops/ms
ClientPb.existUser                       thrpt       3   9.815 ± 2.197  ops/ms
ClientPb.getUser                         thrpt       3   9.243 ± 1.232  ops/ms
ClientPb.listUser                        thrpt       3   8.070 ± 0.714  ops/ms
ClientPb.createUser                       avgt       3   3.385 ± 1.212   ms/op
ClientPb.existUser                        avgt       3   3.386 ± 0.889   ms/op
ClientPb.getUser                          avgt       3   3.381 ± 0.410   ms/op
ClientPb.listUser                         avgt       3   3.994 ± 1.087   ms/op
ClientPb.createUser                     sample  276130   3.472 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.307           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.383           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.950           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.881           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.835           ms/op
ClientPb.existUser                      sample  284483   3.373 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.562           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.578           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.652           ms/op
ClientPb.getUser                        sample  280038   3.426 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.212           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.431           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.987           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.869           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.491           ms/op
ClientPb.listUser                       sample  237411   4.042 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.681           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.855           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.001           ms/op
