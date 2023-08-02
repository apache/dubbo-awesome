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
# Warmup Iteration   1: 1.226 ops/ms
# Warmup Iteration   2: 3.108 ops/ms
# Warmup Iteration   3: 5.753 ops/ms
Iteration   1: 5.650 ops/ms
Iteration   2: 5.959 ops/ms
Iteration   3: 5.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.860 ±(99.9%) 3.326 ops/ms [Average]
  (min, avg, max) = (5.650, 5.860, 5.971), stdev = 0.182
  CI (99.9%): [2.534, 9.186] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.801 ops/ms
# Warmup Iteration   2: 5.462 ops/ms
# Warmup Iteration   3: 6.116 ops/ms
Iteration   1: 6.477 ops/ms
Iteration   2: 6.314 ops/ms
Iteration   3: 6.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.413 ±(99.9%) 1.583 ops/ms [Average]
  (min, avg, max) = (6.314, 6.413, 6.477), stdev = 0.087
  CI (99.9%): [4.831, 7.996] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.722 ops/ms
# Warmup Iteration   2: 4.838 ops/ms
# Warmup Iteration   3: 6.152 ops/ms
Iteration   1: 5.978 ops/ms
Iteration   2: 6.150 ops/ms
Iteration   3: 5.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.017 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (5.922, 6.017, 6.150), stdev = 0.119
  CI (99.9%): [3.853, 8.180] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.709 ops/ms
# Warmup Iteration   2: 4.296 ops/ms
# Warmup Iteration   3: 5.300 ops/ms
Iteration   1: 4.999 ops/ms
Iteration   2: 5.029 ops/ms
Iteration   3: 5.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.114 ±(99.9%) 3.151 ops/ms [Average]
  (min, avg, max) = (4.999, 5.114, 5.312), stdev = 0.173
  CI (99.9%): [1.963, 8.265] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 16.341 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.595 ±(99.9%) 0.015 ms/op
Iteration   1: 5.324 ±(99.9%) 0.010 ms/op
Iteration   2: 5.453 ±(99.9%) 0.008 ms/op
Iteration   3: 5.192 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.323 ±(99.9%) 2.378 ms/op [Average]
  (min, avg, max) = (5.192, 5.323, 5.453), stdev = 0.130
  CI (99.9%): [2.945, 7.701] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 15.476 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.995 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.390 ±(99.9%) 0.007 ms/op
Iteration   1: 4.988 ±(99.9%) 0.012 ms/op
Iteration   2: 5.070 ±(99.9%) 0.010 ms/op
Iteration   3: 5.076 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.045 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (4.988, 5.045, 5.076), stdev = 0.049
  CI (99.9%): [4.148, 5.942] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 14.809 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.917 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.394 ±(99.9%) 0.009 ms/op
Iteration   1: 5.534 ±(99.9%) 0.005 ms/op
Iteration   2: 5.416 ±(99.9%) 0.007 ms/op
Iteration   3: 5.212 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.387 ±(99.9%) 2.972 ms/op [Average]
  (min, avg, max) = (5.212, 5.387, 5.534), stdev = 0.163
  CI (99.9%): [2.415, 8.358] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.454 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.976 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.322 ±(99.9%) 0.012 ms/op
Iteration   1: 6.314 ±(99.9%) 0.014 ms/op
Iteration   2: 6.272 ±(99.9%) 0.009 ms/op
Iteration   3: 6.160 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.249 ±(99.9%) 1.448 ms/op [Average]
  (min, avg, max) = (6.160, 6.249, 6.314), stdev = 0.079
  CI (99.9%): [4.801, 7.697] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 15.777 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.590 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.688 ±(99.9%) 0.022 ms/op
Iteration   1: 5.421 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.277 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   7.135 ms/op
                 createUser·p0.95:   8.176 ms/op
                 createUser·p0.99:   10.395 ms/op
                 createUser·p0.999:  20.837 ms/op
                 createUser·p0.9999: 25.815 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 5.354 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.348 ms/op
                 createUser·p0.99:   9.732 ms/op
                 createUser·p0.999:  24.609 ms/op
                 createUser·p0.9999: 27.296 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   3: 5.314 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   5.046 ms/op
                 createUser·p0.90:   6.545 ms/op
                 createUser·p0.95:   7.471 ms/op
                 createUser·p0.99:   10.125 ms/op
                 createUser·p0.999:  23.159 ms/op
                 createUser·p0.9999: 27.195 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179082
  mean =      5.363 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 84336 
    [ 5.000,  7.500) = 84112 
    [ 7.500, 10.000) = 8616 
    [10.000, 12.500) = 1375 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.997 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.741 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     27.132 ms/op
     p(99.9990) =     27.959 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.097 ±(99.9%) 0.230 ms/op
# Warmup Iteration   2: 5.717 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.169 ±(99.9%) 0.018 ms/op
Iteration   1: 5.125 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.209 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  22.290 ms/op
                 existUser·p0.9999: 25.634 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   2: 5.182 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.265 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.316 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   10.451 ms/op
                 existUser·p0.999:  25.002 ms/op
                 existUser·p0.9999: 31.052 ms/op
                 existUser·p1.00:   31.621 ms/op

Iteration   3: 5.228 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.324 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   10.568 ms/op
                 existUser·p0.999:  15.428 ms/op
                 existUser·p0.9999: 30.671 ms/op
                 existUser·p1.00:   31.588 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185254
  mean =      5.178 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 101915 
    [ 5.000,  7.500) = 74657 
    [ 7.500, 10.000) = 6578 
    [10.000, 12.500) = 1237 
    [12.500, 15.000) = 541 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     16.514 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     31.593 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.677 ±(99.9%) 0.284 ms/op
# Warmup Iteration   2: 6.176 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.567 ±(99.9%) 0.020 ms/op
Iteration   1: 5.305 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.703 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.504 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  22.075 ms/op
                 getUser·p0.9999: 30.230 ms/op
                 getUser·p1.00:   32.571 ms/op

Iteration   2: 5.537 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.012 ms/op
                 getUser·p0.95:   7.946 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  27.073 ms/op
                 getUser·p0.9999: 32.160 ms/op
                 getUser·p1.00:   32.735 ms/op

Iteration   3: 5.454 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.163 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.611 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   11.076 ms/op
                 getUser·p0.999:  25.330 ms/op
                 getUser·p0.9999: 28.512 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176809
  mean =      5.430 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 75045 
    [ 5.000,  7.500) = 90961 
    [ 7.500, 10.000) = 8532 
    [10.000, 12.500) = 1535 
    [12.500, 15.000) = 394 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     10.568 ms/op
     p(99.9000) =     25.494 ms/op
     p(99.9900) =     30.943 ms/op
     p(99.9990) =     32.609 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.184 ±(99.9%) 0.295 ms/op
# Warmup Iteration   2: 7.182 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.972 ±(99.9%) 0.022 ms/op
Iteration   1: 6.286 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.912 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.684 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   12.884 ms/op
                 listUser·p0.999:  25.756 ms/op
                 listUser·p0.9999: 34.322 ms/op
                 listUser·p1.00:   35.324 ms/op

Iteration   2: 6.296 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.162 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.962 ms/op
                 listUser·p0.99:   12.140 ms/op
                 listUser·p0.999:  26.647 ms/op
                 listUser·p0.9999: 29.849 ms/op
                 listUser·p1.00:   31.326 ms/op

Iteration   3: 6.080 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   3.379 ms/op
                 listUser·p0.50:   5.669 ms/op
                 listUser·p0.90:   7.692 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   11.216 ms/op
                 listUser·p0.999:  20.873 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154408
  mean =      6.219 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 12971 
    [ 5.000,  7.500) = 124513 
    [ 7.500, 10.000) = 12674 
    [10.000, 12.500) = 2890 
    [12.500, 15.000) = 811 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 90 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.912 ms/op
     p(50.0000) =      5.849 ms/op
     p(90.0000) =      7.635 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.239 ms/op
     p(99.9000) =     25.133 ms/op
     p(99.9900) =     33.325 ms/op
     p(99.9990) =     35.146 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.860 ± 3.326  ops/ms
ClientPb.existUser                       thrpt       3   6.413 ± 1.583  ops/ms
ClientPb.getUser                         thrpt       3   6.017 ± 2.164  ops/ms
ClientPb.listUser                        thrpt       3   5.114 ± 3.151  ops/ms
ClientPb.createUser                       avgt       3   5.323 ± 2.378   ms/op
ClientPb.existUser                        avgt       3   5.045 ± 0.897   ms/op
ClientPb.getUser                          avgt       3   5.387 ± 2.972   ms/op
ClientPb.listUser                         avgt       3   6.249 ± 1.448   ms/op
ClientPb.createUser                     sample  179082   5.363 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.997           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.063           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.741           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.594           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.132           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  185254   5.178 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.145           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.332           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.191           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.514           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.605           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.621           ms/op
ClientPb.getUser                        sample  176809   5.430 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.145           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.676           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.807           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.568           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.494           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.943           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.735           ms/op
ClientPb.listUser                       sample  154408   6.219 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.912           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.849           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.239           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.133           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.325           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.324           ms/op
