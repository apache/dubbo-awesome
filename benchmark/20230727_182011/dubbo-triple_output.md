# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.752 ops/ms
# Warmup Iteration   2: 4.228 ops/ms
# Warmup Iteration   3: 8.475 ops/ms
Iteration   1: 9.118 ops/ms
Iteration   2: 9.512 ops/ms
Iteration   3: 10.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.553 ±(99.9%) 8.353 ops/ms [Average]
  (min, avg, max) = (9.118, 9.553, 10.031), stdev = 0.458
  CI (99.9%): [1.201, 17.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.220 ops/ms
# Warmup Iteration   2: 7.507 ops/ms
# Warmup Iteration   3: 9.683 ops/ms
Iteration   1: 9.993 ops/ms
Iteration   2: 10.525 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.217 ±(99.9%) 5.037 ops/ms [Average]
  (min, avg, max) = (9.993, 10.217, 10.525), stdev = 0.276
  CI (99.9%): [5.180, 15.254] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 7.995 ops/ms
# Warmup Iteration   3: 9.505 ops/ms
Iteration   1: 9.429 ops/ms
Iteration   2: 9.049 ops/ms
Iteration   3: 9.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.354 ±(99.9%) 5.011 ops/ms [Average]
  (min, avg, max) = (9.049, 9.354, 9.583), stdev = 0.275
  CI (99.9%): [4.343, 14.365] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.653 ops/ms
# Warmup Iteration   2: 7.078 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.308 ops/ms
Iteration   2: 8.299 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.368 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (8.299, 8.368, 8.496), stdev = 0.111
  CI (99.9%): [6.343, 10.393] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.680 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.016 ms/op
Iteration   1: 3.249 ±(99.9%) 0.014 ms/op
Iteration   2: 3.175 ±(99.9%) 0.022 ms/op
Iteration   3: 3.209 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.211 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (3.175, 3.211, 3.249), stdev = 0.037
  CI (99.9%): [2.530, 3.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.834 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.012 ms/op
Iteration   1: 3.169 ±(99.9%) 0.012 ms/op
Iteration   2: 3.131 ±(99.9%) 0.024 ms/op
Iteration   3: 3.123 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.141 ±(99.9%) 0.451 ms/op [Average]
  (min, avg, max) = (3.123, 3.141, 3.169), stdev = 0.025
  CI (99.9%): [2.690, 3.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.625 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.010 ms/op
Iteration   1: 3.376 ±(99.9%) 0.012 ms/op
Iteration   2: 3.331 ±(99.9%) 0.016 ms/op
Iteration   3: 3.232 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.313 ±(99.9%) 1.344 ms/op [Average]
  (min, avg, max) = (3.232, 3.313, 3.376), stdev = 0.074
  CI (99.9%): [1.969, 4.657] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.828 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.009 ms/op
Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
Iteration   2: 3.984 ±(99.9%) 0.010 ms/op
Iteration   3: 3.874 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.914 ±(99.9%) 1.122 ms/op [Average]
  (min, avg, max) = (3.874, 3.914, 3.984), stdev = 0.061
  CI (99.9%): [2.792, 5.035] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.646 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.014 ms/op
Iteration   1: 3.254 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.679 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  10.166 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.528 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.649 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.149 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  13.763 ms/op
                 createUser·p0.9999: 23.298 ms/op
                 createUser·p1.00:   24.314 ms/op

Iteration   3: 3.388 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 21.777 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283276
  mean =      3.386 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3307 
    [ 2.500,  5.000) = 272927 
    [ 5.000,  7.500) = 6159 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     11.551 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.648 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.728 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
Iteration   1: 3.147 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   5.578 ms/op
                 existUser·p0.999:  9.914 ms/op
                 existUser·p0.9999: 26.214 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.841 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.374 ms/op
                 existUser·p0.999:  7.761 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.249 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   6.262 ms/op
                 existUser·p0.999:  12.972 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301391
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12042 
    [ 2.500,  5.000) = 283845 
    [ 5.000,  7.500) = 4696 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     25.227 ms/op
     p(99.9990) =     27.000 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.492 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.628 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  14.644 ms/op
                 getUser·p0.9999: 17.615 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 3.172 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.079 ms/op
                 getUser·p0.999:  7.355 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 3.232 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.925 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 16.384 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293766
  mean =      3.263 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 8064 
    [ 2.500,  3.750) = 261442 
    [ 3.750,  5.000) = 18278 
    [ 5.000,  6.250) = 3343 
    [ 6.250,  7.500) = 1542 
    [ 7.500,  8.750) = 468 
    [ 8.750, 10.000) = 194 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 78 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     11.436 ms/op
     p(99.9900) =     16.677 ms/op
     p(99.9990) =     17.942 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


# JMH version: 1.21
# VM version: JDK 11.0.19, OpenJDK 64-Bit Server VM, 11.0.19+7
# VM invoker: /usr/lib/jvm/temurin-11-jdk-amd64/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.993 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.627 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.171 ±(99.9%) 0.013 ms/op
Iteration   1: 3.847 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  15.182 ms/op
                 listUser·p0.9999: 18.274 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.880 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  15.188 ms/op
                 listUser·p0.9999: 21.324 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.322 ms/op
                 listUser·p0.999:  14.859 ms/op
                 listUser·p0.9999: 18.312 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247107
  mean =      3.883 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 237197 
    [ 5.000,  7.500) = 8100 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.006 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     21.644 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.553 ± 8.353  ops/ms
ClientPb.existUser                       thrpt       3  10.217 ± 5.037  ops/ms
ClientPb.getUser                         thrpt       3   9.354 ± 5.011  ops/ms
ClientPb.listUser                        thrpt       3   8.368 ± 2.025  ops/ms
ClientPb.createUser                       avgt       3   3.211 ± 0.681   ms/op
ClientPb.existUser                        avgt       3   3.141 ± 0.451   ms/op
ClientPb.getUser                          avgt       3   3.313 ± 1.344   ms/op
ClientPb.listUser                         avgt       3   3.914 ± 1.122   ms/op
ClientPb.createUser                     sample  283276   3.386 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.358           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.767           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.551           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.151           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.314           ms/op
ClientPb.existUser                      sample  301391   3.183 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.249           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.088           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.388           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.227           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.263           ms/op
ClientPb.getUser                        sample  293766   3.263 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.663           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.670           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          16.677           ms/op
ClientPb.getUser:getUser·p1.00          sample          18.416           ms/op
ClientPb.listUser                       sample  247107   3.883 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.227           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.006           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.414           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.660           ms/op
