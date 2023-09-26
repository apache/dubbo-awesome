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
# Warmup Iteration   1: 1.729 ops/ms
# Warmup Iteration   2: 3.884 ops/ms
# Warmup Iteration   3: 7.487 ops/ms
Iteration   1: 7.447 ops/ms
Iteration   2: 7.871 ops/ms
Iteration   3: 8.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.783 ±(99.9%) 5.497 ops/ms [Average]
  (min, avg, max) = (7.447, 7.783, 8.031), stdev = 0.301
  CI (99.9%): [2.286, 13.280] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 7.598 ops/ms
# Warmup Iteration   3: 8.106 ops/ms
Iteration   1: 8.312 ops/ms
Iteration   2: 8.323 ops/ms
Iteration   3: 8.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.352 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (8.312, 8.352, 8.422), stdev = 0.061
  CI (99.9%): [7.246, 9.459] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
# Warmup Iteration   2: 6.319 ops/ms
# Warmup Iteration   3: 7.723 ops/ms
Iteration   1: 7.711 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 7.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.807 ±(99.9%) 2.643 ops/ms [Average]
  (min, avg, max) = (7.711, 7.807, 7.974), stdev = 0.145
  CI (99.9%): [5.164, 10.450] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 5.476 ops/ms
# Warmup Iteration   3: 6.561 ops/ms
Iteration   1: 6.637 ops/ms
Iteration   2: 6.693 ops/ms
Iteration   3: 6.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.689 ±(99.9%) 0.919 ops/ms [Average]
  (min, avg, max) = (6.637, 6.689, 6.738), stdev = 0.050
  CI (99.9%): [5.770, 7.609] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.703 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.004 ms/op
Iteration   1: 4.045 ±(99.9%) 0.006 ms/op
Iteration   2: 3.862 ±(99.9%) 0.005 ms/op
Iteration   3: 3.888 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.932 ±(99.9%) 1.803 ms/op [Average]
  (min, avg, max) = (3.862, 3.932, 4.045), stdev = 0.099
  CI (99.9%): [2.128, 5.735] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.427 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.003 ms/op
Iteration   1: 3.870 ±(99.9%) 0.006 ms/op
Iteration   2: 3.819 ±(99.9%) 0.004 ms/op
Iteration   3: 3.966 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.885 ±(99.9%) 1.361 ms/op [Average]
  (min, avg, max) = (3.819, 3.885, 3.966), stdev = 0.075
  CI (99.9%): [2.524, 5.246] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.677 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.004 ms/op
Iteration   1: 4.048 ±(99.9%) 0.007 ms/op
Iteration   2: 3.928 ±(99.9%) 0.006 ms/op
Iteration   3: 3.868 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.948 ±(99.9%) 1.674 ms/op [Average]
  (min, avg, max) = (3.868, 3.948, 4.048), stdev = 0.092
  CI (99.9%): [2.274, 5.622] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.619 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.267 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.944 ±(99.9%) 0.005 ms/op
Iteration   1: 4.788 ±(99.9%) 0.008 ms/op
Iteration   2: 4.732 ±(99.9%) 0.009 ms/op
Iteration   3: 4.823 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.781 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (4.732, 4.781, 4.823), stdev = 0.046
  CI (99.9%): [3.939, 5.623] (assumes normal distribution)


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
# Warmup Iteration   1: 12.384 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.903 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.344 ±(99.9%) 0.018 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  19.825 ms/op
                 createUser·p0.9999: 26.408 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 4.010 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.493 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.860 ms/op
                 createUser·p0.999:  26.542 ms/op
                 createUser·p0.9999: 28.837 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   3: 4.087 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   4.710 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   6.739 ms/op
                 createUser·p0.999:  13.821 ms/op
                 createUser·p0.9999: 29.142 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238283
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 227964 
    [ 5.000,  7.500) = 8587 
    [ 7.500, 10.000) = 807 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 90 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     20.021 ms/op
     p(99.9900) =     28.508 ms/op
     p(99.9990) =     30.396 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 10.799 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
Iteration   1: 3.874 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   7.504 ms/op
                 existUser·p0.999:  14.624 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.858 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  22.025 ms/op
                 existUser·p0.9999: 23.846 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  23.890 ms/op
                 existUser·p0.9999: 27.679 ms/op
                 existUser·p1.00:   28.541 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248337
  mean =      3.863 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 233 
    [ 2.500,  5.000) = 238758 
    [ 5.000,  7.500) = 7200 
    [ 7.500, 10.000) = 1329 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     26.023 ms/op
     p(99.9990) =     27.902 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


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
# Warmup Iteration   1: 13.014 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.373 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.013 ms/op
Iteration   1: 4.035 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  14.871 ms/op
                 getUser·p0.9999: 23.309 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 4.022 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  22.888 ms/op
                 getUser·p0.9999: 25.010 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 4.008 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  13.142 ms/op
                 getUser·p0.9999: 26.150 ms/op
                 getUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238571
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 98 
    [ 2.500,  5.000) = 228475 
    [ 5.000,  7.500) = 7612 
    [ 7.500, 10.000) = 1540 
    [10.000, 12.500) = 378 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     19.108 ms/op
     p(99.9900) =     25.283 ms/op
     p(99.9990) =     26.562 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 15.080 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.362 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.867 ±(99.9%) 0.019 ms/op
Iteration   1: 4.710 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  26.367 ms/op
                 listUser·p0.9999: 32.468 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   2: 4.825 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 22.155 ms/op
                 listUser·p1.00:   32.178 ms/op

Iteration   3: 4.888 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.444 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.464 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  15.827 ms/op
                 listUser·p0.9999: 17.579 ms/op
                 listUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199605
  mean =      4.807 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 156021 
    [ 5.000,  7.500) = 38694 
    [ 7.500, 10.000) = 3704 
    [10.000, 12.500) = 549 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 296 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.135 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     30.812 ms/op
     p(99.9990) =     33.359 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.783 ± 5.497  ops/ms
ClientPb.existUser                       thrpt       3   8.352 ± 1.106  ops/ms
ClientPb.getUser                         thrpt       3   7.807 ± 2.643  ops/ms
ClientPb.listUser                        thrpt       3   6.689 ± 0.919  ops/ms
ClientPb.createUser                       avgt       3   3.932 ± 1.803   ms/op
ClientPb.existUser                        avgt       3   3.885 ± 1.361   ms/op
ClientPb.getUser                          avgt       3   3.948 ± 1.674   ms/op
ClientPb.listUser                         avgt       3   4.781 ± 0.842   ms/op
ClientPb.createUser                     sample  238283   4.026 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.493           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.915           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.508           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.671           ms/op
ClientPb.existUser                      sample  248337   3.863 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.190           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.258           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.709           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.023           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.541           ms/op
ClientPb.getUser                        sample  238571   4.022 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.673           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.850           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.108           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.283           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.525           ms/op
ClientPb.listUser                       sample  199605   4.807 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.135           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.400           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.812           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
