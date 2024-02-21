# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ops/ms
# Warmup Iteration   2: 12.122 ops/ms
# Warmup Iteration   3: 12.157 ops/ms
Iteration   1: 12.832 ops/ms
Iteration   2: 12.815 ops/ms
Iteration   3: 12.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.785 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (12.707, 12.785, 12.832), stdev = 0.068
  CI (99.9%): [11.551, 14.019] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 13.058 ops/ms
# Warmup Iteration   3: 13.188 ops/ms
Iteration   1: 13.202 ops/ms
Iteration   2: 13.310 ops/ms
Iteration   3: 13.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.272 ±(99.9%) 1.106 ops/ms [Average]
  (min, avg, max) = (13.202, 13.272, 13.310), stdev = 0.061
  CI (99.9%): [12.166, 14.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.266 ops/ms
# Warmup Iteration   2: 12.607 ops/ms
# Warmup Iteration   3: 12.814 ops/ms
Iteration   1: 12.889 ops/ms
Iteration   2: 12.906 ops/ms
Iteration   3: 12.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.837 ±(99.9%) 1.926 ops/ms [Average]
  (min, avg, max) = (12.715, 12.837, 12.906), stdev = 0.106
  CI (99.9%): [10.911, 14.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.866 ops/ms
# Warmup Iteration   2: 10.592 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 10.781 ops/ms
Iteration   2: 10.688 ops/ms
Iteration   3: 10.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.739 ±(99.9%) 0.855 ops/ms [Average]
  (min, avg, max) = (10.688, 10.739, 10.781), stdev = 0.047
  CI (99.9%): [9.884, 11.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.540 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.004 ms/op
Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.488 ±(99.9%) 0.304 ms/op [Average]
  (min, avg, max) = (2.469, 2.488, 2.501), stdev = 0.017
  CI (99.9%): [2.183, 2.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.003 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.426 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.427 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.420, 2.427, 2.434), stdev = 0.007
  CI (99.9%): [2.292, 2.561] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.433 ±(99.9%) 0.004 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.447 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.433, 2.447, 2.460), stdev = 0.014
  CI (99.9%): [2.198, 2.696] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.775 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
Iteration   2: 2.980 ±(99.9%) 0.006 ms/op
Iteration   3: 3.006 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.987 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (2.975, 2.987, 3.006), stdev = 0.016
  CI (99.9%): [2.687, 3.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.094 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.006 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  6.621 ms/op
                 createUser·p0.9999: 13.418 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  7.803 ms/op
                 createUser·p0.9999: 12.326 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.028 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.990 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  6.973 ms/op
                 createUser·p0.9999: 11.043 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 388382
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 188773 
    [ 2.500,  3.750) = 196318 
    [ 3.750,  5.000) = 2614 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 120 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.662 ms/op
     p(99.9000) =      6.379 ms/op
     p(99.9900) =     12.864 ms/op
     p(99.9990) =     13.637 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.467 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.005 ms/op
Iteration   1: 2.447 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.637 ms/op
                 existUser·p0.999:  6.922 ms/op
                 existUser·p0.9999: 13.448 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.988 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  8.672 ms/op
                 existUser·p0.9999: 12.731 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.644 ms/op
                 existUser·p0.999:  7.714 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   11.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391585
  mean =      2.449 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 193627 
    [ 2.500,  3.750) = 194686 
    [ 3.750,  5.000) = 2390 
    [ 5.000,  6.250) = 327 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 95 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.633 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.567 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.044 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.476 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.763 ms/op
                 getUser·p0.999:  11.644 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  5.763 ms/op
                 getUser·p0.9999: 12.091 ms/op
                 getUser·p1.00:   12.599 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  6.683 ms/op
                 getUser·p0.9999: 10.466 ms/op
                 getUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388698
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 194557 
    [ 2.500,  3.750) = 190085 
    [ 3.750,  5.000) = 2947 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 121 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =      9.098 ms/op
     p(99.9900) =     12.737 ms/op
     p(99.9990) =     14.100 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.008 ms/op
Iteration   1: 2.957 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.952 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.485 ms/op
                 listUser·p0.9999: 11.226 ms/op
                 listUser·p1.00:   11.796 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  10.371 ms/op
                 listUser·p0.9999: 12.894 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   3: 2.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.855 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.083 ms/op
                 listUser·p0.9999: 10.563 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323469
  mean =      2.965 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 101115 
    [ 2.500,  3.750) = 185072 
    [ 3.750,  5.000) = 30592 
    [ 5.000,  6.250) = 5302 
    [ 6.250,  7.500) = 536 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 307 
    [10.000, 11.250) = 154 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.976 ms/op
     p(99.9990) =     13.091 ms/op
     p(99.9999) =     13.140 ms/op
    p(100.0000) =     13.140 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.785 ± 1.234  ops/ms
ClientPb.existUser                       thrpt       3  13.272 ± 1.106  ops/ms
ClientPb.getUser                         thrpt       3  12.837 ± 1.926  ops/ms
ClientPb.listUser                        thrpt       3  10.739 ± 0.855  ops/ms
ClientPb.createUser                       avgt       3   2.488 ± 0.304   ms/op
ClientPb.existUser                        avgt       3   2.427 ± 0.134   ms/op
ClientPb.getUser                          avgt       3   2.447 ± 0.249   ms/op
ClientPb.listUser                         avgt       3   2.987 ± 0.300   ms/op
ClientPb.createUser                     sample  388382   2.469 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.986           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.560           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.999   sample           6.379           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.864           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.910           ms/op
ClientPb.existUser                      sample  391585   2.449 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.974           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.528           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.943           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.697           ms/op
ClientPb.getUser                        sample  388698   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.711           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.760           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.098           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.737           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  323469   2.965 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.855           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.900           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.976           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.140           ms/op
