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
# Warmup Iteration   1: 4.748 ops/ms
# Warmup Iteration   2: 11.715 ops/ms
# Warmup Iteration   3: 12.129 ops/ms
Iteration   1: 12.445 ops/ms
Iteration   2: 12.515 ops/ms
Iteration   3: 12.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.473 ±(99.9%) 0.674 ops/ms [Average]
  (min, avg, max) = (12.445, 12.473, 12.515), stdev = 0.037
  CI (99.9%): [11.800, 13.147] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.571 ops/ms
# Warmup Iteration   2: 12.817 ops/ms
# Warmup Iteration   3: 12.955 ops/ms
Iteration   1: 12.865 ops/ms
Iteration   2: 12.958 ops/ms
Iteration   3: 12.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.900 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (12.865, 12.900, 12.958), stdev = 0.051
  CI (99.9%): [11.971, 13.828] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.697 ops/ms
# Warmup Iteration   2: 12.284 ops/ms
# Warmup Iteration   3: 12.537 ops/ms
Iteration   1: 12.386 ops/ms
Iteration   2: 12.770 ops/ms
Iteration   3: 12.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.570 ±(99.9%) 3.520 ops/ms [Average]
  (min, avg, max) = (12.386, 12.570, 12.770), stdev = 0.193
  CI (99.9%): [9.050, 16.089] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.205 ops/ms
# Warmup Iteration   2: 10.246 ops/ms
# Warmup Iteration   3: 10.429 ops/ms
Iteration   1: 10.529 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.553 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (10.529, 10.553, 10.599), stdev = 0.040
  CI (99.9%): [9.820, 11.286] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.083 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.537 ±(99.9%) 0.036 ms/op [Average]
  (min, avg, max) = (2.535, 2.537, 2.538), stdev = 0.002
  CI (99.9%): [2.501, 2.573] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.722 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.471 ±(99.9%) 0.004 ms/op
Iteration   2: 2.463 ±(99.9%) 0.003 ms/op
Iteration   3: 2.480 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (2.463, 2.472, 2.480), stdev = 0.008
  CI (99.9%): [2.322, 2.621] (assumes normal distribution)


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.613 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.004 ms/op
Iteration   1: 2.554 ±(99.9%) 0.003 ms/op
Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
Iteration   3: 2.560 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.553 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.545, 2.553, 2.560), stdev = 0.008
  CI (99.9%): [2.410, 2.696] (assumes normal distribution)


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.005 ms/op
Iteration   1: 3.065 ±(99.9%) 0.005 ms/op
Iteration   2: 3.065 ±(99.9%) 0.004 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.059 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (3.045, 3.059, 3.065), stdev = 0.011
  CI (99.9%): [2.851, 3.266] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.334 ms/op
                 createUser·p0.9999: 14.099 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  10.514 ms/op
                 createUser·p0.9999: 13.433 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  8.337 ms/op
                 createUser·p0.9999: 10.011 ms/op
                 createUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378594
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 181381 
    [ 2.500,  3.750) = 192156 
    [ 3.750,  5.000) = 3647 
    [ 5.000,  6.250) = 866 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =     13.823 ms/op
     p(99.9990) =     14.310 ms/op
     p(99.9999) =     14.434 ms/op
    p(100.0000) =     14.434 ms/op


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.491 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.150 ms/op
                 existUser·p0.99:   3.748 ms/op
                 existUser·p0.999:  5.121 ms/op
                 existUser·p0.9999: 13.845 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   2.458 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.633 ms/op
                 existUser·p0.999:  6.449 ms/op
                 existUser·p0.9999: 15.224 ms/op
                 existUser·p1.00:   15.712 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.906 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.228 ms/op
                 existUser·p0.99:   4.120 ms/op
                 existUser·p0.999:  9.276 ms/op
                 existUser·p0.9999: 11.784 ms/op
                 existUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388676
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 193815 
    [ 2.500,  3.750) = 190311 
    [ 3.750,  5.000) = 3572 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =      7.242 ms/op
     p(99.9900) =     14.205 ms/op
     p(99.9990) =     15.647 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  12.044 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.586 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.142 ms/op
                 getUser·p0.95:   3.334 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 13.520 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  8.929 ms/op
                 getUser·p0.9999: 11.262 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376716
  mean =      2.546 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 182963 
    [ 2.500,  3.750) = 187576 
    [ 3.750,  5.000) = 4499 
    [ 5.000,  6.250) = 1182 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 117 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.833 ms/op
     p(99.9990) =     14.184 ms/op
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
# Warmup Iteration   1: 4.945 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.009 ms/op
Iteration   1: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.425 ms/op
                 listUser·p1.00:   13.042 ms/op

Iteration   2: 3.095 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  9.477 ms/op
                 listUser·p0.9999: 14.446 ms/op
                 listUser·p1.00:   14.991 ms/op

Iteration   3: 3.081 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.849 ms/op
                 listUser·p0.999:  10.490 ms/op
                 listUser·p0.9999: 11.649 ms/op
                 listUser·p1.00:   11.846 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311176
  mean =      3.082 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 80901 
    [ 2.500,  3.750) = 186031 
    [ 3.750,  5.000) = 35560 
    [ 5.000,  6.250) = 6855 
    [ 6.250,  7.500) = 1005 
    [ 7.500,  8.750) = 203 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     12.923 ms/op
     p(99.9990) =     14.889 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.473 ± 0.674  ops/ms
ClientPb.existUser                       thrpt       3  12.900 ± 0.929  ops/ms
ClientPb.getUser                         thrpt       3  12.570 ± 3.520  ops/ms
ClientPb.listUser                        thrpt       3  10.553 ± 0.733  ops/ms
ClientPb.createUser                       avgt       3   2.537 ± 0.036   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.150   ms/op
ClientPb.getUser                          avgt       3   2.553 ± 0.143   ms/op
ClientPb.listUser                         avgt       3   3.059 ± 0.208   ms/op
ClientPb.createUser                     sample  378594   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.890           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.471           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.823           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.434           ms/op
ClientPb.existUser                      sample  388676   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.871           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.015           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.158           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.242           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.205           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.712           ms/op
ClientPb.getUser                        sample  376716   2.546 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.576           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.978           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.833           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  311176   3.082 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.825           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.994           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.759           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.880           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.923           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.991           ms/op
