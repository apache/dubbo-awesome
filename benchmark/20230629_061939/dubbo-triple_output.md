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
# Warmup Iteration   1: 2.458 ops/ms
# Warmup Iteration   2: 5.797 ops/ms
# Warmup Iteration   3: 9.358 ops/ms
Iteration   1: 9.929 ops/ms
Iteration   2: 10.378 ops/ms
Iteration   3: 9.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.051 ±(99.9%) 5.223 ops/ms [Average]
  (min, avg, max) = (9.845, 10.051, 10.378), stdev = 0.286
  CI (99.9%): [4.828, 15.274] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.939 ops/ms
# Warmup Iteration   2: 9.601 ops/ms
# Warmup Iteration   3: 10.265 ops/ms
Iteration   1: 10.343 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.427 ±(99.9%) 1.426 ops/ms [Average]
  (min, avg, max) = (10.343, 10.427, 10.498), stdev = 0.078
  CI (99.9%): [9.000, 11.853] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.799 ops/ms
# Warmup Iteration   2: 8.612 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 9.974 ops/ms
Iteration   2: 10.233 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.109 ±(99.9%) 2.373 ops/ms [Average]
  (min, avg, max) = (9.974, 10.109, 10.233), stdev = 0.130
  CI (99.9%): [7.736, 12.482] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.127 ops/ms
# Warmup Iteration   2: 7.771 ops/ms
# Warmup Iteration   3: 8.394 ops/ms
Iteration   1: 8.813 ops/ms
Iteration   2: 8.740 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.720 ±(99.9%) 1.897 ops/ms [Average]
  (min, avg, max) = (8.608, 8.720, 8.813), stdev = 0.104
  CI (99.9%): [6.824, 10.617] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.236 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.006 ms/op
Iteration   2: 3.249 ±(99.9%) 0.004 ms/op
Iteration   3: 3.148 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.215 ±(99.9%) 1.063 ms/op [Average]
  (min, avg, max) = (3.148, 3.215, 3.249), stdev = 0.058
  CI (99.9%): [2.152, 4.279] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.913 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.009 ms/op
Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
Iteration   3: 3.026 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.072 ±(99.9%) 1.292 ms/op [Average]
  (min, avg, max) = (3.026, 3.072, 3.154), stdev = 0.071
  CI (99.9%): [1.780, 4.365] (assumes normal distribution)


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
# Warmup Iteration   1: 7.679 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.004 ms/op
Iteration   1: 3.366 ±(99.9%) 0.008 ms/op
Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
Iteration   3: 3.255 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.275 ±(99.9%) 1.501 ms/op [Average]
  (min, avg, max) = (3.205, 3.275, 3.366), stdev = 0.082
  CI (99.9%): [1.774, 4.776] (assumes normal distribution)


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
# Warmup Iteration   1: 10.059 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.477 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.004 ms/op
Iteration   1: 3.843 ±(99.9%) 0.007 ms/op
Iteration   2: 3.783 ±(99.9%) 0.008 ms/op
Iteration   3: 3.850 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.825 ±(99.9%) 0.676 ms/op [Average]
  (min, avg, max) = (3.783, 3.825, 3.850), stdev = 0.037
  CI (99.9%): [3.150, 4.501] (assumes normal distribution)


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
# Warmup Iteration   1: 8.719 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.009 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  18.940 ms/op
                 createUser·p0.9999: 22.500 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  15.808 ms/op
                 createUser·p0.9999: 25.786 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.502 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 30.638 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304894
  mean =      3.150 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23687 
    [ 2.500,  5.000) = 276522 
    [ 5.000,  7.500) = 3700 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =     15.683 ms/op
     p(99.9900) =     25.903 ms/op
     p(99.9990) =     31.084 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 7.289 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.379 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 21.791 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.143 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  12.938 ms/op
                 existUser·p0.9999: 30.305 ms/op
                 existUser·p1.00:   31.883 ms/op

Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  10.264 ms/op
                 existUser·p0.9999: 21.756 ms/op
                 existUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308244
  mean =      3.110 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27428 
    [ 2.500,  5.000) = 275268 
    [ 5.000,  7.500) = 4719 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 152 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     29.890 ms/op
     p(99.9990) =     30.797 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 8.259 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.449 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.011 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  15.221 ms/op
                 getUser·p0.9999: 20.561 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.242 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.524 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.398 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  16.037 ms/op
                 getUser·p0.9999: 21.178 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303290
  mean =      3.164 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14588 
    [ 2.500,  5.000) = 282739 
    [ 5.000,  7.500) = 4849 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     15.626 ms/op
     p(99.9900) =     21.376 ms/op
     p(99.9990) =     22.052 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 8.880 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.013 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  15.748 ms/op
                 listUser·p0.9999: 21.673 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.769 ms/op
                 listUser·p0.999:  14.703 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 3.843 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.414 ms/op
                 listUser·p0.9999: 18.929 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254869
  mean =      3.768 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 80 
    [ 2.500,  5.000) = 248327 
    [ 5.000,  7.500) = 4642 
    [ 7.500, 10.000) = 1202 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.909 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     15.370 ms/op
     p(99.9900) =     19.874 ms/op
     p(99.9990) =     22.106 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.051 ± 5.223  ops/ms
ClientPb.existUser                       thrpt       3  10.427 ± 1.426  ops/ms
ClientPb.getUser                         thrpt       3  10.109 ± 2.373  ops/ms
ClientPb.listUser                        thrpt       3   8.720 ± 1.897  ops/ms
ClientPb.createUser                       avgt       3   3.215 ± 1.063   ms/op
ClientPb.existUser                        avgt       3   3.072 ± 1.292   ms/op
ClientPb.getUser                          avgt       3   3.275 ± 1.501   ms/op
ClientPb.listUser                         avgt       3   3.825 ± 0.676   ms/op
ClientPb.createUser                     sample  304894   3.150 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.683           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.903           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.850           ms/op
ClientPb.existUser                      sample  308244   3.110 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.061           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.665           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.890           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  303290   3.164 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.069           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.882           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.626           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.376           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.184           ms/op
ClientPb.listUser                       sample  254869   3.768 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.909           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.767           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.370           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.874           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
