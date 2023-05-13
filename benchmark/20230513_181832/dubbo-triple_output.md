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
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 6.676 ops/ms
# Warmup Iteration   3: 9.356 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.002 ops/ms
Iteration   3: 10.267 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.159 ±(99.9%) 2.539 ops/ms [Average]
  (min, avg, max) = (10.002, 10.159, 10.267), stdev = 0.139
  CI (99.9%): [7.620, 12.698] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ops/ms
# Warmup Iteration   2: 8.954 ops/ms
# Warmup Iteration   3: 10.273 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.330 ops/ms
Iteration   3: 10.315 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.392 ±(99.9%) 2.185 ops/ms [Average]
  (min, avg, max) = (10.315, 10.392, 10.530), stdev = 0.120
  CI (99.9%): [8.206, 12.577] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.607 ops/ms
# Warmup Iteration   2: 9.139 ops/ms
# Warmup Iteration   3: 9.758 ops/ms
Iteration   1: 9.822 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 10.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.139 ±(99.9%) 5.360 ops/ms [Average]
  (min, avg, max) = (9.822, 10.139, 10.403), stdev = 0.294
  CI (99.9%): [4.778, 15.499] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ops/ms
# Warmup Iteration   2: 7.883 ops/ms
# Warmup Iteration   3: 8.661 ops/ms
Iteration   1: 8.770 ops/ms
Iteration   2: 8.669 ops/ms
Iteration   3: 8.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.688 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (8.626, 8.688, 8.770), stdev = 0.074
  CI (99.9%): [7.337, 10.040] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.018 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.484 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.003 ms/op
Iteration   1: 3.104 ±(99.9%) 0.005 ms/op
Iteration   2: 3.182 ±(99.9%) 0.003 ms/op
Iteration   3: 3.168 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.151 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.104, 3.151, 3.182), stdev = 0.041
  CI (99.9%): [2.399, 3.904] (assumes normal distribution)


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
# Warmup Iteration   1: 7.482 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.001 ms/op
Iteration   1: 3.185 ±(99.9%) 0.005 ms/op
Iteration   2: 2.984 ±(99.9%) 0.008 ms/op
Iteration   3: 2.951 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.040 ±(99.9%) 2.310 ms/op [Average]
  (min, avg, max) = (2.951, 3.040, 3.185), stdev = 0.127
  CI (99.9%): [0.730, 5.350] (assumes normal distribution)


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
# Warmup Iteration   1: 9.188 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.004 ms/op
Iteration   1: 3.266 ±(99.9%) 0.005 ms/op
Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
Iteration   3: 3.141 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.170 ±(99.9%) 1.539 ms/op [Average]
  (min, avg, max) = (3.105, 3.170, 3.266), stdev = 0.084
  CI (99.9%): [1.632, 4.709] (assumes normal distribution)


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
# Warmup Iteration   1: 8.903 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.005 ms/op
Iteration   1: 3.838 ±(99.9%) 0.003 ms/op
Iteration   2: 3.722 ±(99.9%) 0.007 ms/op
Iteration   3: 3.724 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.761 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.722, 3.761, 3.838), stdev = 0.067
  CI (99.9%): [2.543, 4.980] (assumes normal distribution)


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
# Warmup Iteration   1: 7.674 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.159 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.207 ms/op
                 createUser·p0.95:   3.461 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  9.208 ms/op
                 createUser·p0.9999: 23.268 ms/op
                 createUser·p1.00:   23.724 ms/op

Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  18.874 ms/op
                 createUser·p0.9999: 21.564 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  14.844 ms/op
                 createUser·p0.9999: 18.402 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303366
  mean =      3.161 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22859 
    [ 2.500,  5.000) = 275202 
    [ 5.000,  7.500) = 4290 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 191 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     16.726 ms/op
     p(99.9900) =     21.955 ms/op
     p(99.9990) =     23.690 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 7.522 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.008 ms/op
Iteration   1: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  12.728 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  9.781 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.585 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  12.917 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309179
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23406 
    [ 2.500,  5.000) = 280130 
    [ 5.000,  7.500) = 4788 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 149 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     20.909 ms/op
     p(99.9990) =     22.240 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.964 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.232 ±(99.9%) 0.009 ms/op
Iteration   1: 3.214 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  17.219 ms/op
                 getUser·p0.9999: 19.992 ms/op
                 getUser·p1.00:   20.873 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   5.333 ms/op
                 getUser·p0.999:  10.712 ms/op
                 getUser·p0.9999: 21.682 ms/op
                 getUser·p1.00:   22.118 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   5.295 ms/op
                 getUser·p0.999:  9.689 ms/op
                 getUser·p0.9999: 21.290 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305412
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13567 
    [ 2.500,  5.000) = 286428 
    [ 5.000,  7.500) = 4607 
    [ 7.500, 10.000) = 331 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.843 ms/op
     p(99.9900) =     21.329 ms/op
     p(99.9990) =     22.049 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 8.454 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.993 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.011 ms/op
Iteration   1: 3.715 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.772 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.259 ms/op
                 listUser·p0.9999: 15.876 ms/op
                 listUser·p1.00:   15.925 ms/op

Iteration   3: 3.798 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.170 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.435 ms/op
                 listUser·p0.9999: 13.976 ms/op
                 listUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255017
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 70 
    [ 2.500,  3.750) = 187847 
    [ 3.750,  5.000) = 58418 
    [ 5.000,  6.250) = 4245 
    [ 6.250,  7.500) = 2803 
    [ 7.500,  8.750) = 724 
    [ 8.750, 10.000) = 311 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 118 
    [12.500, 13.750) = 169 
    [13.750, 15.000) = 122 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.159 ± 2.539  ops/ms
ClientPb.existUser                       thrpt       3  10.392 ± 2.185  ops/ms
ClientPb.getUser                         thrpt       3  10.139 ± 5.360  ops/ms
ClientPb.listUser                        thrpt       3   8.688 ± 1.351  ops/ms
ClientPb.createUser                       avgt       3   3.151 ± 0.753   ms/op
ClientPb.existUser                        avgt       3   3.040 ± 2.310   ms/op
ClientPb.getUser                          avgt       3   3.170 ± 1.539   ms/op
ClientPb.listUser                         avgt       3   3.761 ± 1.219   ms/op
ClientPb.createUser                     sample  303366   3.161 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.053           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.726           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.955           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.724           ms/op
ClientPb.existUser                      sample  309179   3.103 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.077           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.363           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.431           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.730           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.909           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.233           ms/op
ClientPb.getUser                        sample  305412   3.141 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.057           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.031           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.843           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.329           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.543           ms/op
ClientPb.listUser                       sample  255017   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.517           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.579           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.399           ms/op
