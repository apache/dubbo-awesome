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
# Warmup Iteration   1: 5.169 ops/ms
# Warmup Iteration   2: 12.309 ops/ms
# Warmup Iteration   3: 12.469 ops/ms
Iteration   1: 12.657 ops/ms
Iteration   2: 12.649 ops/ms
Iteration   3: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.678 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (12.649, 12.678, 12.727), stdev = 0.043
  CI (99.9%): [11.896, 13.459] (assumes normal distribution)


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
# Warmup Iteration   1: 8.596 ops/ms
# Warmup Iteration   2: 13.242 ops/ms
# Warmup Iteration   3: 13.170 ops/ms
Iteration   1: 13.009 ops/ms
Iteration   2: 13.013 ops/ms
Iteration   3: 13.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.020 ±(99.9%) 0.307 ops/ms [Average]
  (min, avg, max) = (13.009, 13.020, 13.040), stdev = 0.017
  CI (99.9%): [12.713, 13.328] (assumes normal distribution)


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
# Warmup Iteration   1: 7.991 ops/ms
# Warmup Iteration   2: 12.608 ops/ms
# Warmup Iteration   3: 12.826 ops/ms
Iteration   1: 12.763 ops/ms
Iteration   2: 12.743 ops/ms
Iteration   3: 12.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.793 ±(99.9%) 1.257 ops/ms [Average]
  (min, avg, max) = (12.743, 12.793, 12.872), stdev = 0.069
  CI (99.9%): [11.535, 14.050] (assumes normal distribution)


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
# Warmup Iteration   1: 7.062 ops/ms
# Warmup Iteration   2: 10.442 ops/ms
# Warmup Iteration   3: 10.727 ops/ms
Iteration   1: 10.711 ops/ms
Iteration   2: 10.669 ops/ms
Iteration   3: 10.710 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.697 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (10.669, 10.697, 10.711), stdev = 0.024
  CI (99.9%): [10.258, 11.135] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.004 ms/op
Iteration   1: 2.579 ±(99.9%) 0.004 ms/op
Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
Iteration   3: 2.546 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.563 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (2.546, 2.563, 2.579), stdev = 0.016
  CI (99.9%): [2.262, 2.863] (assumes normal distribution)


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.466 ±(99.9%) 0.005 ms/op
Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
Iteration   3: 2.469 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.465 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.461, 2.465, 2.469), stdev = 0.004
  CI (99.9%): [2.393, 2.537] (assumes normal distribution)


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.516 ±(99.9%) 0.005 ms/op
Iteration   1: 2.536 ±(99.9%) 0.004 ms/op
Iteration   2: 2.523 ±(99.9%) 0.004 ms/op
Iteration   3: 2.514 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.525 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (2.514, 2.525, 2.536), stdev = 0.011
  CI (99.9%): [2.326, 2.723] (assumes normal distribution)


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
# Warmup Iteration   1: 4.690 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
Iteration   2: 3.029 ±(99.9%) 0.007 ms/op
Iteration   3: 3.044 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.029, 3.036, 3.044), stdev = 0.008
  CI (99.9%): [2.898, 3.175] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.690 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.532 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.006 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.826 ms/op
                 createUser·p0.999:  12.006 ms/op
                 createUser·p0.9999: 14.339 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.699 ms/op
                 createUser·p0.999:  9.179 ms/op
                 createUser·p0.9999: 12.735 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.100 ms/op
                 createUser·p0.999:  8.366 ms/op
                 createUser·p0.9999: 12.672 ms/op
                 createUser·p1.00:   13.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379102
  mean =      2.530 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 182002 
    [ 2.500,  3.750) = 192400 
    [ 3.750,  5.000) = 3798 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =      8.531 ms/op
     p(99.9900) =     13.715 ms/op
     p(99.9990) =     14.736 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.600 ms/op
                 existUser·p0.999:  11.999 ms/op
                 existUser·p0.9999: 16.346 ms/op
                 existUser·p1.00:   16.974 ms/op

Iteration   2: 2.506 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.236 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 13.148 ms/op
                 existUser·p1.00:   14.287 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.437 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.248 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  7.626 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383226
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 195044 
    [ 2.500,  3.750) = 182632 
    [ 3.750,  5.000) = 4441 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.099 ms/op
     p(99.9900) =     13.664 ms/op
     p(99.9990) =     16.701 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  5.366 ms/op
                 getUser·p0.9999: 13.941 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 2.522 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.838 ms/op
                 getUser·p0.9999: 13.841 ms/op
                 getUser·p1.00:   15.516 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.547 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  8.005 ms/op
                 getUser·p0.9999: 11.111 ms/op
                 getUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383782
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 190060 
    [ 2.500,  3.750) = 187873 
    [ 3.750,  5.000) = 4367 
    [ 5.000,  6.250) = 1025 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =      6.291 ms/op
     p(99.9900) =     13.773 ms/op
     p(99.9990) =     14.393 ms/op
     p(99.9999) =     15.516 ms/op
    p(100.0000) =     15.516 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.082 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 12.311 ms/op
                 listUser·p1.00:   12.616 ms/op

Iteration   2: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.595 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.999 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  8.849 ms/op
                 listUser·p0.9999: 10.735 ms/op
                 listUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317768
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 91658 
    [ 2.500,  3.750) = 185370 
    [ 3.750,  5.000) = 33134 
    [ 5.000,  6.250) = 6247 
    [ 6.250,  7.500) = 513 
    [ 7.500,  8.750) = 290 
    [ 8.750, 10.000) = 239 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.403 ms/op
     p(99.9990) =     12.484 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.678 ± 0.782  ops/ms
ClientPb.existUser                       thrpt       3  13.020 ± 0.307  ops/ms
ClientPb.getUser                         thrpt       3  12.793 ± 1.257  ops/ms
ClientPb.listUser                        thrpt       3  10.697 ± 0.438  ops/ms
ClientPb.createUser                       avgt       3   2.563 ± 0.301   ms/op
ClientPb.existUser                        avgt       3   2.465 ± 0.072   ms/op
ClientPb.getUser                          avgt       3   2.525 ± 0.198   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.139   ms/op
ClientPb.createUser                     sample  379102   2.530 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.776           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.207           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.715           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.844           ms/op
ClientPb.existUser                      sample  383226   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.701           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.973           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.099           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.664           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.974           ms/op
ClientPb.getUser                        sample  383782   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.547           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.291           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.773           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.516           ms/op
ClientPb.listUser                       sample  317768   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.924           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.546           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.616           ms/op
