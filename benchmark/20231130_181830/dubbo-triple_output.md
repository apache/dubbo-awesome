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
# Warmup Iteration   1: 4.927 ops/ms
# Warmup Iteration   2: 12.032 ops/ms
# Warmup Iteration   3: 12.092 ops/ms
Iteration   1: 12.326 ops/ms
Iteration   2: 12.304 ops/ms
Iteration   3: 12.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.375 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (12.304, 12.375, 12.496), stdev = 0.105
  CI (99.9%): [10.460, 14.290] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.122 ops/ms
# Warmup Iteration   2: 12.966 ops/ms
# Warmup Iteration   3: 12.721 ops/ms
Iteration   1: 13.017 ops/ms
Iteration   2: 12.981 ops/ms
Iteration   3: 12.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.958 ±(99.9%) 1.327 ops/ms [Average]
  (min, avg, max) = (12.877, 12.958, 13.017), stdev = 0.073
  CI (99.9%): [11.631, 14.285] (assumes normal distribution)


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
# Warmup Iteration   1: 7.798 ops/ms
# Warmup Iteration   2: 12.515 ops/ms
# Warmup Iteration   3: 12.683 ops/ms
Iteration   1: 12.637 ops/ms
Iteration   2: 12.637 ops/ms
Iteration   3: 12.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.682 ±(99.9%) 1.412 ops/ms [Average]
  (min, avg, max) = (12.637, 12.682, 12.771), stdev = 0.077
  CI (99.9%): [11.270, 14.093] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.599 ops/ms
# Warmup Iteration   2: 10.306 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.527 ops/ms
Iteration   3: 10.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.511 ±(99.9%) 0.350 ops/ms [Average]
  (min, avg, max) = (10.490, 10.511, 10.527), stdev = 0.019
  CI (99.9%): [10.161, 10.861] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.580 ±(99.9%) 0.005 ms/op
Iteration   2: 2.587 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.547, 2.571, 2.587), stdev = 0.021
  CI (99.9%): [2.183, 2.960] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.864 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.004 ms/op
Iteration   1: 2.526 ±(99.9%) 0.003 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.511 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.487, 2.511, 2.526), stdev = 0.021
  CI (99.9%): [2.129, 2.893] (assumes normal distribution)


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
# Warmup Iteration   1: 4.145 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.004 ms/op
Iteration   1: 2.583 ±(99.9%) 0.004 ms/op
Iteration   2: 2.522 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.539 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (2.510, 2.539, 2.583), stdev = 0.039
  CI (99.9%): [1.823, 3.254] (assumes normal distribution)


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
# Warmup Iteration   1: 4.722 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.005 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
Iteration   3: 3.056 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.067 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.056, 3.067, 3.086), stdev = 0.017
  CI (99.9%): [2.758, 3.376] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.548 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   4.030 ms/op
                 createUser·p0.999:  11.323 ms/op
                 createUser·p0.9999: 13.990 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  8.869 ms/op
                 createUser·p0.9999: 13.082 ms/op
                 createUser·p1.00:   13.468 ms/op

Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   3.973 ms/op
                 createUser·p0.999:  8.585 ms/op
                 createUser·p0.9999: 14.768 ms/op
                 createUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375208
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 177019 
    [ 2.500,  3.750) = 192812 
    [ 3.750,  5.000) = 4320 
    [ 5.000,  6.250) = 579 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      2.630 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     14.090 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.045 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  5.225 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   2: 2.508 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 22.618 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.016 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  9.097 ms/op
                 existUser·p0.9999: 12.523 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383073
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 185825 
    [ 2.500,  5.000) = 196307 
    [ 5.000,  7.500) = 564 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      7.253 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     23.140 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.917 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.574 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  5.931 ms/op
                 getUser·p0.9999: 14.565 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 13.169 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  8.756 ms/op
                 getUser·p0.9999: 11.076 ms/op
                 getUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381148
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 186969 
    [ 2.500,  3.750) = 188837 
    [ 3.750,  5.000) = 4196 
    [ 5.000,  6.250) = 590 
    [ 6.250,  7.500) = 91 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 125 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.241 ms/op
     p(99.9900) =     13.595 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.739 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.009 ms/op
Iteration   1: 3.077 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  8.913 ms/op
                 listUser·p0.9999: 10.778 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   2: 3.104 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.030 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 12.103 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   3: 3.111 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 13.445 ms/op
                 listUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 309674
  mean =      3.097 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 77467 
    [ 2.500,  3.750) = 186558 
    [ 3.750,  5.000) = 37127 
    [ 5.000,  6.250) = 6835 
    [ 6.250,  7.500) = 926 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.049 ms/op
     p(99.9900) =     12.158 ms/op
     p(99.9990) =     15.110 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.375 ± 1.915  ops/ms
ClientPb.existUser                       thrpt       3  12.958 ± 1.327  ops/ms
ClientPb.getUser                         thrpt       3  12.682 ± 1.412  ops/ms
ClientPb.listUser                        thrpt       3  10.511 ± 0.350  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.389   ms/op
ClientPb.existUser                        avgt       3   2.511 ± 0.382   ms/op
ClientPb.getUser                          avgt       3   2.539 ± 0.716   ms/op
ClientPb.listUser                         avgt       3   3.067 ± 0.309   ms/op
ClientPb.createUser                     sample  375208   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.630           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.618           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.090           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.155           ms/op
ClientPb.existUser                      sample  383073   2.503 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.964           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.568           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.253           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.976           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.200           ms/op
ClientPb.getUser                        sample  381148   2.516 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.841           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.056           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.595           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  309674   3.097 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.872           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.049           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.158           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.712           ms/op
