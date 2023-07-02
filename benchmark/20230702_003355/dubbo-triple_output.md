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
# Warmup Iteration   1: 1.877 ops/ms
# Warmup Iteration   2: 5.059 ops/ms
# Warmup Iteration   3: 8.612 ops/ms
Iteration   1: 9.219 ops/ms
Iteration   2: 9.517 ops/ms
Iteration   3: 8.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.225 ±(99.9%) 5.292 ops/ms [Average]
  (min, avg, max) = (8.937, 9.225, 9.517), stdev = 0.290
  CI (99.9%): [3.932, 14.517] (assumes normal distribution)


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
# Warmup Iteration   1: 2.760 ops/ms
# Warmup Iteration   2: 8.333 ops/ms
# Warmup Iteration   3: 9.389 ops/ms
Iteration   1: 9.364 ops/ms
Iteration   2: 9.371 ops/ms
Iteration   3: 9.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.417 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (9.364, 9.417, 9.517), stdev = 0.087
  CI (99.9%): [7.835, 11.000] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.686 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 9.152 ops/ms
Iteration   2: 9.269 ops/ms
Iteration   3: 9.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.189 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (9.148, 9.189, 9.269), stdev = 0.069
  CI (99.9%): [7.938, 10.441] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.982 ops/ms
# Warmup Iteration   2: 7.174 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 8.019 ops/ms
Iteration   2: 7.955 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.952 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (7.883, 7.952, 8.019), stdev = 0.068
  CI (99.9%): [6.707, 9.197] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.589 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.592 ±(99.9%) 0.006 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
Iteration   2: 3.403 ±(99.9%) 0.008 ms/op
Iteration   3: 3.400 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.408 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.400, 3.408, 3.422), stdev = 0.012
  CI (99.9%): [3.195, 3.622] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.554 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.005 ms/op
Iteration   1: 3.399 ±(99.9%) 0.007 ms/op
Iteration   2: 3.384 ±(99.9%) 0.007 ms/op
Iteration   3: 3.356 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.380 ±(99.9%) 0.399 ms/op [Average]
  (min, avg, max) = (3.356, 3.380, 3.399), stdev = 0.022
  CI (99.9%): [2.981, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 9.398 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.007 ms/op
Iteration   1: 3.547 ±(99.9%) 0.009 ms/op
Iteration   2: 3.523 ±(99.9%) 0.008 ms/op
Iteration   3: 3.361 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.477 ±(99.9%) 1.845 ms/op [Average]
  (min, avg, max) = (3.361, 3.477, 3.547), stdev = 0.101
  CI (99.9%): [1.632, 5.322] (assumes normal distribution)


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
# Warmup Iteration   1: 11.827 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.495 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.007 ms/op
Iteration   1: 4.279 ±(99.9%) 0.007 ms/op
Iteration   2: 4.183 ±(99.9%) 0.009 ms/op
Iteration   3: 3.993 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.152 ±(99.9%) 2.655 ms/op [Average]
  (min, avg, max) = (3.993, 4.152, 4.279), stdev = 0.146
  CI (99.9%): [1.497, 6.806] (assumes normal distribution)


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
# Warmup Iteration   1: 11.162 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.785 ±(99.9%) 0.014 ms/op
Iteration   1: 3.613 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.675 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   5.014 ms/op
                 createUser·p0.99:   6.980 ms/op
                 createUser·p0.999:  20.523 ms/op
                 createUser·p0.9999: 23.883 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.437 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  22.149 ms/op
                 createUser·p0.9999: 25.779 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.764 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.226 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  21.398 ms/op
                 createUser·p0.9999: 28.558 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266571
  mean =      3.600 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6902 
    [ 2.500,  5.000) = 248070 
    [ 5.000,  7.500) = 10493 
    [ 7.500, 10.000) = 695 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.869 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     21.224 ms/op
     p(99.9900) =     27.012 ms/op
     p(99.9990) =     29.371 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 9.916 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.011 ms/op
Iteration   1: 3.331 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  21.310 ms/op
                 existUser·p0.9999: 28.723 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  23.853 ms/op
                 existUser·p0.9999: 26.030 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   3: 3.437 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  9.677 ms/op
                 existUser·p0.9999: 28.577 ms/op
                 existUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281184
  mean =      3.413 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7540 
    [ 2.500,  5.000) = 266830 
    [ 5.000,  7.500) = 5736 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     12.310 ms/op
     p(99.9900) =     28.263 ms/op
     p(99.9990) =     30.120 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 10.204 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.018 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.012 ms/op
Iteration   1: 3.605 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  23.383 ms/op
                 getUser·p0.9999: 27.967 ms/op
                 getUser·p1.00:   28.967 ms/op

Iteration   2: 3.531 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.978 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  9.791 ms/op
                 getUser·p0.9999: 25.255 ms/op
                 getUser·p1.00:   27.460 ms/op

Iteration   3: 3.720 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  26.978 ms/op
                 getUser·p0.9999: 32.014 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 265269
  mean =      3.617 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3672 
    [ 2.500,  5.000) = 252583 
    [ 5.000,  7.500) = 7740 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     31.209 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 12.260 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.804 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.015 ms/op
Iteration   1: 4.344 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.112 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  22.652 ms/op
                 listUser·p0.9999: 26.182 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.246 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.810 ms/op
                 listUser·p0.999:  17.678 ms/op
                 listUser·p0.9999: 21.999 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.120 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.812 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.686 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  17.179 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226580
  mean =      4.235 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62 
    [ 2.500,  5.000) = 211614 
    [ 5.000,  7.500) = 12084 
    [ 7.500, 10.000) = 2019 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      4.076 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.874 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     27.156 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.225 ± 5.292  ops/ms
ClientPb.existUser                       thrpt       3   9.417 ± 1.582  ops/ms
ClientPb.getUser                         thrpt       3   9.189 ± 1.251  ops/ms
ClientPb.listUser                        thrpt       3   7.952 ± 1.245  ops/ms
ClientPb.createUser                       avgt       3   3.408 ± 0.213   ms/op
ClientPb.existUser                        avgt       3   3.380 ± 0.399   ms/op
ClientPb.getUser                          avgt       3   3.477 ± 1.845   ms/op
ClientPb.listUser                         avgt       3   4.152 ± 2.655   ms/op
ClientPb.createUser                     sample  266571   3.600 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.675           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.869           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.224           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.012           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  281184   3.413 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.212           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.029           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.310           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.263           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.441           ms/op
ClientPb.getUser                        sample  265269   3.617 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.337           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.678           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  226580   4.235 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.076           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.874           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.186           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.838           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
