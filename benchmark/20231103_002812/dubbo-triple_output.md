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
# Warmup Iteration   1: 2.425 ops/ms
# Warmup Iteration   2: 6.169 ops/ms
# Warmup Iteration   3: 9.148 ops/ms
Iteration   1: 9.313 ops/ms
Iteration   2: 9.749 ops/ms
Iteration   3: 9.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.586 ±(99.9%) 4.348 ops/ms [Average]
  (min, avg, max) = (9.313, 9.586, 9.749), stdev = 0.238
  CI (99.9%): [5.239, 13.934] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.514 ops/ms
# Warmup Iteration   2: 9.041 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.154 ops/ms
Iteration   2: 10.011 ops/ms
Iteration   3: 10.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.066 ±(99.9%) 1.401 ops/ms [Average]
  (min, avg, max) = (10.011, 10.066, 10.154), stdev = 0.077
  CI (99.9%): [8.665, 11.467] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 9.159 ops/ms
# Warmup Iteration   3: 9.269 ops/ms
Iteration   1: 9.788 ops/ms
Iteration   2: 9.739 ops/ms
Iteration   3: 9.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.736 ±(99.9%) 0.990 ops/ms [Average]
  (min, avg, max) = (9.680, 9.736, 9.788), stdev = 0.054
  CI (99.9%): [8.746, 10.726] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.108 ops/ms
# Warmup Iteration   2: 7.810 ops/ms
# Warmup Iteration   3: 8.338 ops/ms
Iteration   1: 8.181 ops/ms
Iteration   2: 8.267 ops/ms
Iteration   3: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.299 ±(99.9%) 2.493 ops/ms [Average]
  (min, avg, max) = (8.181, 8.299, 8.449), stdev = 0.137
  CI (99.9%): [5.806, 10.792] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.070 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.651 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.006 ms/op
Iteration   1: 3.228 ±(99.9%) 0.004 ms/op
Iteration   2: 3.346 ±(99.9%) 0.003 ms/op
Iteration   3: 3.278 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.284 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.228, 3.284, 3.346), stdev = 0.059
  CI (99.9%): [2.204, 4.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.444 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.338 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.003 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.170 ±(99.9%) 0.005 ms/op
Iteration   3: 3.098 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.149 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.098, 3.149, 3.177), stdev = 0.044
  CI (99.9%): [2.351, 3.947] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.324 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.002 ms/op
Iteration   1: 3.214 ±(99.9%) 0.004 ms/op
Iteration   2: 3.225 ±(99.9%) 0.003 ms/op
Iteration   3: 3.272 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.237 ±(99.9%) 0.564 ms/op [Average]
  (min, avg, max) = (3.214, 3.237, 3.272), stdev = 0.031
  CI (99.9%): [2.673, 3.802] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.021 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.863 ±(99.9%) 0.004 ms/op
Iteration   1: 3.772 ±(99.9%) 0.006 ms/op
Iteration   2: 3.833 ±(99.9%) 0.005 ms/op
Iteration   3: 3.825 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.810 ±(99.9%) 0.608 ms/op [Average]
  (min, avg, max) = (3.772, 3.810, 3.833), stdev = 0.033
  CI (99.9%): [3.202, 4.418] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.000 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.008 ms/op
Iteration   1: 3.397 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  16.937 ms/op
                 createUser·p0.9999: 20.204 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.270 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.470 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  17.638 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   3: 3.251 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  13.485 ms/op
                 createUser·p0.9999: 21.053 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290236
  mean =      3.305 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16455 
    [ 2.500,  5.000) = 267386 
    [ 5.000,  7.500) = 5426 
    [ 7.500, 10.000) = 395 
    [10.000, 12.500) = 207 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     21.461 ms/op
     p(99.9990) =     22.744 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.047 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.009 ms/op
Iteration   1: 3.218 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.908 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 18.614 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   2: 3.190 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.151 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  15.004 ms/op
                 existUser·p0.9999: 20.904 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   3: 3.190 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  15.417 ms/op
                 existUser·p0.9999: 21.452 ms/op
                 existUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299935
  mean =      3.199 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15606 
    [ 2.500,  5.000) = 279608 
    [ 5.000,  7.500) = 3718 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 208 
    [12.500, 15.000) = 177 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     20.808 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.227 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.009 ms/op
Iteration   1: 3.245 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  14.352 ms/op
                 getUser·p0.9999: 18.495 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 3.291 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.325 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  15.314 ms/op
                 getUser·p0.9999: 17.615 ms/op
                 getUser·p1.00:   22.413 ms/op

Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.368 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   7.257 ms/op
                 getUser·p0.999:  14.172 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289910
  mean =      3.308 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8062 
    [ 2.500,  5.000) = 275180 
    [ 5.000,  7.500) = 5204 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      6.513 ms/op
     p(99.9000) =     15.060 ms/op
     p(99.9900) =     19.336 ms/op
     p(99.9990) =     21.830 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.342 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.732 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  19.186 ms/op
                 listUser·p0.9999: 22.814 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 3.888 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.074 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.847 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  11.269 ms/op
                 listUser·p0.9999: 16.018 ms/op
                 listUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246692
  mean =      3.890 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 89 
    [ 2.500,  5.000) = 240553 
    [ 5.000,  7.500) = 4450 
    [ 7.500, 10.000) = 803 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.732 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     24.692 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.586 ± 4.348  ops/ms
ClientPb.existUser                       thrpt       3  10.066 ± 1.401  ops/ms
ClientPb.getUser                         thrpt       3   9.736 ± 0.990  ops/ms
ClientPb.listUser                        thrpt       3   8.299 ± 2.493  ops/ms
ClientPb.createUser                       avgt       3   3.284 ± 1.080   ms/op
ClientPb.existUser                        avgt       3   3.149 ± 0.798   ms/op
ClientPb.getUser                          avgt       3   3.237 ± 0.564   ms/op
ClientPb.listUser                         avgt       3   3.810 ± 0.608   ms/op
ClientPb.createUser                     sample  290236   3.305 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.124           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.275           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.581           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.970           ms/op
ClientPb.existUser                      sample  299935   3.199 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.908           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.352           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.808           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.446           ms/op
ClientPb.getUser                        sample  289910   3.308 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.325           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.199           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.513           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.060           ms/op
ClientPb.getUser:getUser·p0.9999        sample          19.336           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.413           ms/op
ClientPb.listUser                       sample  246692   3.890 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.732           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.336           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.856           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
