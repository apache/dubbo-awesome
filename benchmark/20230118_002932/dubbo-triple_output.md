# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.680 ops/ms
# Warmup Iteration   2: 6.799 ops/ms
# Warmup Iteration   3: 9.371 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.223 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (10.194, 10.223, 10.252), stdev = 0.029
  CI (99.9%): [9.697, 10.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ops/ms
# Warmup Iteration   2: 9.642 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 10.593 ops/ms
Iteration   3: 10.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.388 ±(99.9%) 4.602 ops/ms [Average]
  (min, avg, max) = (10.106, 10.388, 10.593), stdev = 0.252
  CI (99.9%): [5.786, 14.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.531 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 10.082 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 10.057 ops/ms
Iteration   3: 10.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.108 ±(99.9%) 3.231 ops/ms [Average]
  (min, avg, max) = (9.963, 10.108, 10.305), stdev = 0.177
  CI (99.9%): [6.878, 13.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.694 ops/ms
# Warmup Iteration   2: 7.721 ops/ms
# Warmup Iteration   3: 8.628 ops/ms
Iteration   1: 8.722 ops/ms
Iteration   2: 8.558 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.592 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (8.496, 8.592, 8.722), stdev = 0.117
  CI (99.9%): [6.465, 10.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.007 ms/op
Iteration   1: 3.201 ±(99.9%) 0.006 ms/op
Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
Iteration   3: 3.091 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.120 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (3.067, 3.120, 3.201), stdev = 0.072
  CI (99.9%): [1.813, 4.427] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.772 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.004 ms/op
Iteration   1: 3.071 ±(99.9%) 0.005 ms/op
Iteration   2: 2.946 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.012 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (2.946, 3.012, 3.071), stdev = 0.063
  CI (99.9%): [1.865, 4.160] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.824 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.298 ±(99.9%) 0.002 ms/op
Iteration   1: 3.212 ±(99.9%) 0.006 ms/op
Iteration   2: 3.141 ±(99.9%) 0.004 ms/op
Iteration   3: 3.213 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.189 ±(99.9%) 0.759 ms/op [Average]
  (min, avg, max) = (3.141, 3.189, 3.213), stdev = 0.042
  CI (99.9%): [2.430, 3.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.868 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.843 ±(99.9%) 0.004 ms/op
Iteration   1: 3.695 ±(99.9%) 0.007 ms/op
Iteration   2: 3.766 ±(99.9%) 0.009 ms/op
Iteration   3: 3.697 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.719 ±(99.9%) 0.737 ms/op [Average]
  (min, avg, max) = (3.695, 3.719, 3.766), stdev = 0.040
  CI (99.9%): [2.982, 4.457] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.547 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.249 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 20.087 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  13.286 ms/op
                 createUser·p0.9999: 22.346 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  14.582 ms/op
                 createUser·p0.9999: 23.158 ms/op
                 createUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304631
  mean =      3.149 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18743 
    [ 2.500,  5.000) = 281528 
    [ 5.000,  7.500) = 3639 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     22.070 ms/op
     p(99.9990) =     23.719 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.074 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.023 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  8.664 ms/op
                 existUser·p0.9999: 20.932 ms/op
                 existUser·p1.00:   22.315 ms/op

Iteration   2: 2.969 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.125 ms/op
                 existUser·p0.95:   3.367 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  10.982 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   23.331 ms/op

Iteration   3: 3.037 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   5.875 ms/op
                 existUser·p0.999:  14.746 ms/op
                 existUser·p0.9999: 20.429 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315588
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28858 
    [ 2.500,  5.000) = 281730 
    [ 5.000,  7.500) = 4219 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     14.192 ms/op
     p(99.9900) =     22.231 ms/op
     p(99.9990) =     23.190 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.926 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.328 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.010 ms/op
Iteration   1: 3.281 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  18.153 ms/op
                 getUser·p0.9999: 21.234 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.151 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.546 ms/op
                 getUser·p0.999:  19.790 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.114 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.555 ms/op
                 getUser·p0.99:   5.276 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 17.233 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301679
  mean =      3.181 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20356 
    [ 2.500,  5.000) = 274096 
    [ 5.000,  7.500) = 6145 
    [ 7.500, 10.000) = 479 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     15.586 ms/op
     p(99.9900) =     21.916 ms/op
     p(99.9990) =     22.805 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.476 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.743 ±(99.9%) 0.011 ms/op
Iteration   1: 3.716 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.575 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.350 ms/op
                 listUser·p0.999:  16.250 ms/op
                 listUser·p0.9999: 19.883 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   2: 3.638 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.055 ms/op
                 listUser·p0.99:   6.882 ms/op
                 listUser·p0.999:  11.977 ms/op
                 listUser·p0.9999: 12.917 ms/op
                 listUser·p1.00:   13.386 ms/op

Iteration   3: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  11.796 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259621
  mean =      3.697 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 252306 
    [ 5.000,  7.500) = 5411 
    [ 7.500, 10.000) = 1247 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.575 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     19.277 ms/op
     p(99.9990) =     20.474 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.223 ± 0.526  ops/ms
ClientPb.existUser                       thrpt       3  10.388 ± 4.602  ops/ms
ClientPb.getUser                         thrpt       3  10.108 ± 3.231  ops/ms
ClientPb.listUser                        thrpt       3   8.592 ± 2.127  ops/ms
ClientPb.createUser                       avgt       3   3.120 ± 1.307   ms/op
ClientPb.existUser                        avgt       3   3.012 ± 1.148   ms/op
ClientPb.getUser                          avgt       3   3.189 ± 0.759   ms/op
ClientPb.listUser                         avgt       3   3.719 ± 0.737   ms/op
ClientPb.createUser                     sample  304631   3.149 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.096           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.565           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.070           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.986           ms/op
ClientPb.existUser                      sample  315588   3.044 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.664           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.277           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.366           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.192           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.231           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.331           ms/op
ClientPb.getUser                        sample  301679   3.181 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.061           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.586           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.916           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.938           ms/op
ClientPb.listUser                       sample  259621   3.697 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.575           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.304           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.277           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.742           ms/op
