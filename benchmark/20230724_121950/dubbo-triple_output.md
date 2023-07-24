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
# Warmup Iteration   1: 2.643 ops/ms
# Warmup Iteration   2: 6.108 ops/ms
# Warmup Iteration   3: 9.271 ops/ms
Iteration   1: 9.732 ops/ms
Iteration   2: 9.817 ops/ms
Iteration   3: 9.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.842 ±(99.9%) 2.261 ops/ms [Average]
  (min, avg, max) = (9.732, 9.842, 9.976), stdev = 0.124
  CI (99.9%): [7.581, 12.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ops/ms
# Warmup Iteration   2: 9.475 ops/ms
# Warmup Iteration   3: 10.011 ops/ms
Iteration   1: 10.098 ops/ms
Iteration   2: 10.420 ops/ms
Iteration   3: 10.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.175 ±(99.9%) 3.959 ops/ms [Average]
  (min, avg, max) = (10.007, 10.175, 10.420), stdev = 0.217
  CI (99.9%): [6.216, 14.134] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.138 ops/ms
# Warmup Iteration   2: 9.160 ops/ms
# Warmup Iteration   3: 9.485 ops/ms
Iteration   1: 10.037 ops/ms
Iteration   2: 9.937 ops/ms
Iteration   3: 10.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.025 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (9.937, 10.025, 10.100), stdev = 0.082
  CI (99.9%): [8.527, 11.523] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.169 ops/ms
# Warmup Iteration   2: 7.618 ops/ms
# Warmup Iteration   3: 8.392 ops/ms
Iteration   1: 8.446 ops/ms
Iteration   2: 8.347 ops/ms
Iteration   3: 8.485 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.426 ±(99.9%) 1.299 ops/ms [Average]
  (min, avg, max) = (8.347, 8.426, 8.485), stdev = 0.071
  CI (99.9%): [7.127, 9.725] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.081 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.592 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.352 ±(99.9%) 0.005 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
Iteration   2: 3.193 ±(99.9%) 0.004 ms/op
Iteration   3: 3.114 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.141 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.114, 3.141, 3.193), stdev = 0.045
  CI (99.9%): [2.319, 3.962] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.815 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.231 ±(99.9%) 0.005 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
Iteration   3: 3.150 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (3.031, 3.077, 3.150), stdev = 0.064
  CI (99.9%): [1.911, 4.243] (assumes normal distribution)


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
# Warmup Iteration   1: 7.945 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.004 ms/op
Iteration   1: 3.184 ±(99.9%) 0.004 ms/op
Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
Iteration   3: 3.205 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.182 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.158, 3.182, 3.205), stdev = 0.023
  CI (99.9%): [2.759, 3.606] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.011 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.006 ms/op
Iteration   1: 3.814 ±(99.9%) 0.008 ms/op
Iteration   2: 3.721 ±(99.9%) 0.010 ms/op
Iteration   3: 3.796 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.777 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.721, 3.777, 3.814), stdev = 0.049
  CI (99.9%): [2.880, 4.674] (assumes normal distribution)


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
# Warmup Iteration   1: 8.143 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.009 ms/op
Iteration   1: 3.220 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  19.246 ms/op
                 createUser·p0.9999: 23.499 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.278 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.442 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  9.905 ms/op
                 createUser·p0.9999: 29.818 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 3.294 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.532 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  18.280 ms/op
                 createUser·p0.9999: 27.109 ms/op
                 createUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294053
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21005 
    [ 2.500,  5.000) = 268206 
    [ 5.000,  7.500) = 4096 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     19.066 ms/op
     p(99.9900) =     27.787 ms/op
     p(99.9990) =     30.571 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.044 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
Iteration   1: 3.194 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.046 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.302 ms/op
                 existUser·p0.999:  10.138 ms/op
                 existUser·p0.9999: 23.134 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.111 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 24.632 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  13.255 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304594
  mean =      3.149 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17489 
    [ 2.500,  5.000) = 281455 
    [ 5.000,  7.500) = 4820 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     12.517 ms/op
     p(99.9900) =     23.449 ms/op
     p(99.9990) =     24.966 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.322 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.328 ±(99.9%) 0.009 ms/op
Iteration   1: 3.217 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  10.181 ms/op
                 getUser·p0.9999: 23.691 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.314 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.946 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.177 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  13.513 ms/op
                 getUser·p0.9999: 28.257 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  10.739 ms/op
                 getUser·p0.9999: 23.729 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294764
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17477 
    [ 2.500,  5.000) = 269569 
    [ 5.000,  7.500) = 6962 
    [ 7.500, 10.000) = 450 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.865 ms/op
     p(99.9000) =     10.270 ms/op
     p(99.9900) =     26.330 ms/op
     p(99.9990) =     28.686 ms/op
     p(99.9999) =     31.195 ms/op
    p(100.0000) =     31.195 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.160 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
Iteration   1: 3.761 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  15.265 ms/op
                 listUser·p0.9999: 20.430 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.729 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.174 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  14.160 ms/op
                 listUser·p0.9999: 19.829 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 3.819 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  12.927 ms/op
                 listUser·p0.9999: 19.502 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254515
  mean =      3.770 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 247016 
    [ 5.000,  7.500) = 6137 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.921 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     19.977 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.842 ± 2.261  ops/ms
ClientPb.existUser                       thrpt       3  10.175 ± 3.959  ops/ms
ClientPb.getUser                         thrpt       3  10.025 ± 1.498  ops/ms
ClientPb.listUser                        thrpt       3   8.426 ± 1.299  ops/ms
ClientPb.createUser                       avgt       3   3.141 ± 0.821   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 1.166   ms/op
ClientPb.getUser                          avgt       3   3.182 ± 0.424   ms/op
ClientPb.listUser                         avgt       3   3.777 ± 0.897   ms/op
ClientPb.createUser                     sample  294053   3.264 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.186           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.039           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.066           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.787           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.588           ms/op
ClientPb.existUser                      sample  304594   3.149 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.850           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.686           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.489           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.449           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.559           ms/op
ClientPb.getUser                        sample  294764   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.946           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.865           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.270           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.330           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.195           ms/op
ClientPb.listUser                       sample  254515   3.770 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.921           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
