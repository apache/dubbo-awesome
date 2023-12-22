# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 12.168 ops/ms
# Warmup Iteration   3: 12.483 ops/ms
Iteration   1: 12.846 ops/ms
Iteration   2: 13.050 ops/ms
Iteration   3: 12.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.926 ±(99.9%) 1.985 ops/ms [Average]
  (min, avg, max) = (12.846, 12.926, 13.050), stdev = 0.109
  CI (99.9%): [10.941, 14.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.488 ops/ms
# Warmup Iteration   2: 13.201 ops/ms
# Warmup Iteration   3: 13.271 ops/ms
Iteration   1: 13.490 ops/ms
Iteration   2: 13.353 ops/ms
Iteration   3: 13.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.337 ±(99.9%) 2.965 ops/ms [Average]
  (min, avg, max) = (13.166, 13.337, 13.490), stdev = 0.163
  CI (99.9%): [10.372, 16.301] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.513 ops/ms
# Warmup Iteration   2: 12.876 ops/ms
# Warmup Iteration   3: 12.925 ops/ms
Iteration   1: 13.153 ops/ms
Iteration   2: 13.054 ops/ms
Iteration   3: 13.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.136 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (13.054, 13.136, 13.201), stdev = 0.075
  CI (99.9%): [11.765, 14.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.733 ops/ms
# Warmup Iteration   2: 10.480 ops/ms
# Warmup Iteration   3: 10.772 ops/ms
Iteration   1: 10.789 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.885 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.784 ±(99.9%) 1.881 ops/ms [Average]
  (min, avg, max) = (10.679, 10.784, 10.885), stdev = 0.103
  CI (99.9%): [8.904, 12.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.065 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.494 ±(99.9%) 0.004 ms/op
Iteration   2: 2.482 ±(99.9%) 0.003 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.485 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.480, 2.485, 2.494), stdev = 0.007
  CI (99.9%): [2.353, 2.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.429 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.004 ms/op
Iteration   1: 2.418 ±(99.9%) 0.004 ms/op
Iteration   2: 2.401 ±(99.9%) 0.004 ms/op
Iteration   3: 2.394 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.405 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.394, 2.405, 2.418), stdev = 0.012
  CI (99.9%): [2.182, 2.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.425 ±(99.9%) 0.003 ms/op
Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
Iteration   3: 2.426 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.432 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.425, 2.432, 2.445), stdev = 0.011
  CI (99.9%): [2.225, 2.640] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.471 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.007 ms/op
Iteration   1: 2.974 ±(99.9%) 0.004 ms/op
Iteration   2: 2.978 ±(99.9%) 0.005 ms/op
Iteration   3: 2.944 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.965 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (2.944, 2.965, 2.978), stdev = 0.019
  CI (99.9%): [2.626, 3.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.597 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.006 ms/op
Iteration   1: 2.417 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   2.499 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.052 ms/op
                 createUser·p0.99:   3.606 ms/op
                 createUser·p0.999:  11.022 ms/op
                 createUser·p0.9999: 13.222 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.967 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.088 ms/op
                 createUser·p0.99:   3.539 ms/op
                 createUser·p0.999:  6.456 ms/op
                 createUser·p0.9999: 12.992 ms/op
                 createUser·p1.00:   13.386 ms/op

Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.507 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  6.158 ms/op
                 createUser·p0.9999: 10.338 ms/op
                 createUser·p1.00:   10.535 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 393090
  mean =      2.440 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 195353 
    [ 2.500,  3.750) = 194699 
    [ 3.750,  5.000) = 2372 
    [ 5.000,  6.250) = 166 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.617 ms/op
     p(99.9000) =      8.682 ms/op
     p(99.9900) =     13.004 ms/op
     p(99.9990) =     13.391 ms/op
     p(99.9999) =     13.664 ms/op
    p(100.0000) =     13.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.451 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.408 ±(99.9%) 0.005 ms/op
Iteration   1: 2.410 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  5.484 ms/op
                 existUser·p0.9999: 13.496 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  5.781 ms/op
                 existUser·p0.9999: 10.746 ms/op
                 existUser·p1.00:   11.043 ms/op

Iteration   3: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.707 ms/op
                 existUser·p0.999:  8.852 ms/op
                 existUser·p0.9999: 12.042 ms/op
                 existUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394171
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 197162 
    [ 2.500,  3.750) = 194052 
    [ 3.750,  5.000) = 2299 
    [ 5.000,  6.250) = 182 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.568 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =     13.018 ms/op
     p(99.9990) =     13.863 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.876 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.072 ms/op
                 getUser·p0.99:   3.514 ms/op
                 getUser·p0.999:  6.255 ms/op
                 getUser·p0.9999: 17.333 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 2.438 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.944 ms/op
                 getUser·p0.50:   2.466 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.764 ms/op
                 getUser·p0.999:  5.396 ms/op
                 getUser·p0.9999: 14.317 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.407 ms/op
                 getUser·p0.9999: 10.984 ms/op
                 getUser·p1.00:   11.305 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389506
  mean =      2.462 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 97 
    [ 1.250,  2.500) = 195932 
    [ 2.500,  3.750) = 188744 
    [ 3.750,  5.000) = 3621 
    [ 5.000,  6.250) = 680 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.879 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     14.673 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
Iteration   1: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.437 ms/op
                 listUser·p0.9999: 12.622 ms/op
                 listUser·p1.00:   13.320 ms/op

Iteration   2: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.813 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.798 ms/op
                 listUser·p0.9999: 11.637 ms/op
                 listUser·p1.00:   12.567 ms/op

Iteration   3: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.975 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.257 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 322362
  mean =      2.975 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 98654 
    [ 2.500,  3.750) = 185946 
    [ 3.750,  5.000) = 30489 
    [ 5.000,  6.250) = 5752 
    [ 6.250,  7.500) = 676 
    [ 7.500,  8.750) = 175 
    [ 8.750, 10.000) = 313 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.448 ms/op
     p(99.9900) =     12.071 ms/op
     p(99.9990) =     13.067 ms/op
     p(99.9999) =     13.320 ms/op
    p(100.0000) =     13.320 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.926 ± 1.985  ops/ms
ClientPb.existUser                       thrpt       3  13.337 ± 2.965  ops/ms
ClientPb.getUser                         thrpt       3  13.136 ± 1.371  ops/ms
ClientPb.listUser                        thrpt       3  10.784 ± 1.881  ops/ms
ClientPb.createUser                       avgt       3   2.485 ± 0.133   ms/op
ClientPb.existUser                        avgt       3   2.405 ± 0.222   ms/op
ClientPb.getUser                          avgt       3   2.432 ± 0.207   ms/op
ClientPb.listUser                         avgt       3   2.965 ± 0.339   ms/op
ClientPb.createUser                     sample  393090   2.440 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.966           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.682           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.004           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.664           ms/op
ClientPb.existUser                      sample  394171   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.926           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.499           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.799           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.018           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.926           ms/op
ClientPb.getUser                        sample  389506   2.462 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.839           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.947           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.673           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.317           ms/op
ClientPb.listUser                       sample  322362   2.975 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.867           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.904           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.448           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.071           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.320           ms/op
