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
# Warmup Iteration   1: 5.075 ops/ms
# Warmup Iteration   2: 12.040 ops/ms
# Warmup Iteration   3: 12.142 ops/ms
Iteration   1: 12.312 ops/ms
Iteration   2: 12.394 ops/ms
Iteration   3: 12.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.415 ±(99.9%) 2.105 ops/ms [Average]
  (min, avg, max) = (12.312, 12.415, 12.540), stdev = 0.115
  CI (99.9%): [10.310, 14.520] (assumes normal distribution)


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
# Warmup Iteration   1: 8.149 ops/ms
# Warmup Iteration   2: 12.923 ops/ms
# Warmup Iteration   3: 12.871 ops/ms
Iteration   1: 12.987 ops/ms
Iteration   2: 12.919 ops/ms
Iteration   3: 12.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.941 ±(99.9%) 0.721 ops/ms [Average]
  (min, avg, max) = (12.918, 12.941, 12.987), stdev = 0.040
  CI (99.9%): [12.221, 13.662] (assumes normal distribution)


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
# Warmup Iteration   1: 7.484 ops/ms
# Warmup Iteration   2: 12.270 ops/ms
# Warmup Iteration   3: 12.582 ops/ms
Iteration   1: 12.733 ops/ms
Iteration   2: 12.641 ops/ms
Iteration   3: 12.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.673 ±(99.9%) 0.943 ops/ms [Average]
  (min, avg, max) = (12.641, 12.673, 12.733), stdev = 0.052
  CI (99.9%): [11.730, 13.616] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.640 ops/ms
# Warmup Iteration   2: 10.353 ops/ms
# Warmup Iteration   3: 10.477 ops/ms
Iteration   1: 10.492 ops/ms
Iteration   2: 10.623 ops/ms
Iteration   3: 10.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.566 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (10.492, 10.566, 10.623), stdev = 0.067
  CI (99.9%): [9.348, 11.784] (assumes normal distribution)


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.631 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.600 ±(99.9%) 0.005 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.540 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.552 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (2.517, 2.552, 2.600), stdev = 0.043
  CI (99.9%): [1.770, 3.335] (assumes normal distribution)


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
# Warmup Iteration   1: 3.740 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.476 ±(99.9%) 0.004 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.487 ±(99.9%) 0.163 ms/op [Average]
  (min, avg, max) = (2.480, 2.487, 2.497), stdev = 0.009
  CI (99.9%): [2.324, 2.651] (assumes normal distribution)


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.004 ms/op
Iteration   1: 2.501 ±(99.9%) 0.003 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.502 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.498 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.492, 2.498, 2.502), stdev = 0.006
  CI (99.9%): [2.395, 2.602] (assumes normal distribution)


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
# Warmup Iteration   1: 4.802 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.005 ms/op
Iteration   1: 3.019 ±(99.9%) 0.005 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.058 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.045 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.019, 3.045, 3.058), stdev = 0.022
  CI (99.9%): [2.641, 3.449] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.576 ±(99.9%) 0.006 ms/op
Iteration   1: 2.551 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.700 ms/op
                 createUser·p0.999:  11.803 ms/op
                 createUser·p0.9999: 13.582 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.121 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  9.773 ms/op
                 createUser·p0.9999: 12.781 ms/op
                 createUser·p1.00:   13.091 ms/op

Iteration   3: 2.578 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.985 ms/op
                 createUser·p0.9999: 10.437 ms/op
                 createUser·p1.00:   10.748 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373901
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 178695 
    [ 2.500,  3.750) = 189901 
    [ 3.750,  5.000) = 3982 
    [ 5.000,  6.250) = 727 
    [ 6.250,  7.500) = 150 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.109 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      9.390 ms/op
     p(99.9900) =     13.311 ms/op
     p(99.9990) =     14.174 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  7.613 ms/op
                 existUser·p0.9999: 14.057 ms/op
                 existUser·p1.00:   15.237 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  7.127 ms/op
                 existUser·p0.9999: 12.599 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  9.085 ms/op
                 existUser·p0.9999: 11.472 ms/op
                 existUser·p1.00:   12.304 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387682
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 44 
    [ 1.250,  2.500) = 192681 
    [ 2.500,  3.750) = 191037 
    [ 3.750,  5.000) = 3129 
    [ 5.000,  6.250) = 350 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      7.514 ms/op
     p(99.9900) =     13.177 ms/op
     p(99.9990) =     14.717 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.778 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 14.161 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.314 ms/op
                 getUser·p0.99:   4.702 ms/op
                 getUser·p0.999:  9.844 ms/op
                 getUser·p0.9999: 13.703 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   3: 2.540 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.067 ms/op
                 getUser·p0.999:  9.078 ms/op
                 getUser·p0.9999: 12.190 ms/op
                 getUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377657
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 183051 
    [ 2.500,  3.750) = 187398 
    [ 3.750,  5.000) = 5673 
    [ 5.000,  6.250) = 966 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      9.131 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.773 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.009 ms/op
Iteration   1: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.265 ms/op
                 listUser·p0.9999: 11.286 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.781 ms/op
                 listUser·p0.9999: 11.182 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.883 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.144 ms/op
                 listUser·p0.9999: 11.187 ms/op
                 listUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315382
  mean =      3.041 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 85958 
    [ 2.500,  3.750) = 189075 
    [ 3.750,  5.000) = 33127 
    [ 5.000,  6.250) = 5816 
    [ 6.250,  7.500) = 631 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 276 
    [10.000, 11.250) = 168 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.414 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.181 ms/op
     p(99.9990) =     11.925 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.415 ± 2.105  ops/ms
ClientPb.existUser                       thrpt       3  12.941 ± 0.721  ops/ms
ClientPb.getUser                         thrpt       3  12.673 ± 0.943  ops/ms
ClientPb.listUser                        thrpt       3  10.566 ± 1.218  ops/ms
ClientPb.createUser                       avgt       3   2.552 ± 0.783   ms/op
ClientPb.existUser                        avgt       3   2.487 ± 0.163   ms/op
ClientPb.getUser                          avgt       3   2.498 ± 0.103   ms/op
ClientPb.listUser                         avgt       3   3.045 ± 0.404   ms/op
ClientPb.createUser                     sample  373901   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.869           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.109           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.390           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.311           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  387682   2.474 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.756           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.514           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.177           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.237           ms/op
ClientPb.getUser                        sample  377657   2.540 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.558           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.568           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.248           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.131           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  315382   3.041 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.883           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.414           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.181           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.042           ms/op
