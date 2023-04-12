# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.572 ops/ms
# Warmup Iteration   2: 5.326 ops/ms
# Warmup Iteration   3: 9.137 ops/ms
Iteration   1: 9.949 ops/ms
Iteration   2: 9.682 ops/ms
Iteration   3: 10.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.903 ±(99.9%) 3.685 ops/ms [Average]
  (min, avg, max) = (9.682, 9.903, 10.078), stdev = 0.202
  CI (99.9%): [6.218, 13.588] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 9.270 ops/ms
# Warmup Iteration   3: 10.067 ops/ms
Iteration   1: 10.421 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.449 ±(99.9%) 4.033 ops/ms [Average]
  (min, avg, max) = (10.243, 10.449, 10.683), stdev = 0.221
  CI (99.9%): [6.415, 14.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.479 ops/ms
# Warmup Iteration   2: 8.997 ops/ms
# Warmup Iteration   3: 9.878 ops/ms
Iteration   1: 9.863 ops/ms
Iteration   2: 9.895 ops/ms
Iteration   3: 9.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.883 ±(99.9%) 0.318 ops/ms [Average]
  (min, avg, max) = (9.863, 9.883, 9.895), stdev = 0.017
  CI (99.9%): [9.564, 10.201] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ops/ms
# Warmup Iteration   2: 7.514 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 8.465 ops/ms
Iteration   2: 8.502 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.526 ±(99.9%) 1.388 ops/ms [Average]
  (min, avg, max) = (8.465, 8.526, 8.611), stdev = 0.076
  CI (99.9%): [7.138, 9.914] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.033 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.003 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
Iteration   3: 3.205 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.182 ±(99.9%) 0.695 ms/op [Average]
  (min, avg, max) = (3.138, 3.182, 3.205), stdev = 0.038
  CI (99.9%): [2.488, 3.877] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.478 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.161 ±(99.9%) 0.004 ms/op
Iteration   1: 3.152 ±(99.9%) 0.005 ms/op
Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
Iteration   3: 3.010 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.093 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.010, 3.093, 3.152), stdev = 0.074
  CI (99.9%): [1.748, 4.439] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.260 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.003 ms/op
Iteration   1: 3.114 ±(99.9%) 0.005 ms/op
Iteration   2: 3.264 ±(99.9%) 0.006 ms/op
Iteration   3: 3.184 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.188 ±(99.9%) 1.370 ms/op [Average]
  (min, avg, max) = (3.114, 3.188, 3.264), stdev = 0.075
  CI (99.9%): [1.817, 4.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.289 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.005 ms/op
Iteration   1: 3.690 ±(99.9%) 0.005 ms/op
Iteration   2: 3.694 ±(99.9%) 0.009 ms/op
Iteration   3: 3.832 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 1.478 ms/op [Average]
  (min, avg, max) = (3.690, 3.739, 3.832), stdev = 0.081
  CI (99.9%): [2.261, 5.217] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.991 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.010 ms/op
Iteration   1: 3.188 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  19.051 ms/op
                 createUser·p0.9999: 22.018 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  8.922 ms/op
                 createUser·p0.9999: 24.936 ms/op
                 createUser·p1.00:   25.395 ms/op

Iteration   3: 3.403 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.290 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  14.056 ms/op
                 createUser·p0.9999: 19.110 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294300
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27499 
    [ 2.500,  5.000) = 258590 
    [ 5.000,  7.500) = 7401 
    [ 7.500, 10.000) = 367 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.290 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.823 ms/op
     p(99.9900) =     23.925 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.591 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.389 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.008 ms/op
Iteration   1: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.912 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.195 ms/op
                 existUser·p0.95:   3.248 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 2.997 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.142 ms/op
                 existUser·p0.95:   3.293 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.015 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 19.770 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314138
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23772 
    [ 2.500,  5.000) = 286908 
    [ 5.000,  7.500) = 2735 
    [ 7.500, 10.000) = 230 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.912 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.224 ms/op
     p(95.0000) =      3.383 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     12.728 ms/op
     p(99.9900) =     24.148 ms/op
     p(99.9990) =     26.107 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.782 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.279 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.585 ms/op
                 getUser·p0.999:  15.718 ms/op
                 getUser·p0.9999: 20.389 ms/op
                 getUser·p1.00:   20.742 ms/op

Iteration   2: 3.177 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  13.315 ms/op
                 getUser·p0.9999: 22.274 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.369 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  16.624 ms/op
                 getUser·p0.9999: 23.216 ms/op
                 getUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293189
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20556 
    [ 2.500,  5.000) = 265013 
    [ 5.000,  7.500) = 6614 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     16.047 ms/op
     p(99.9900) =     22.099 ms/op
     p(99.9990) =     23.822 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.707 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.012 ms/op
Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.482 ms/op
                 listUser·p0.999:  15.942 ms/op
                 listUser·p0.9999: 19.525 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 3.755 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.850 ms/op
                 listUser·p0.9999: 15.601 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   3: 3.681 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.076 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  11.583 ms/op
                 listUser·p0.9999: 14.255 ms/op
                 listUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259273
  mean =      3.703 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 38 
    [ 2.500,  3.750) = 212652 
    [ 3.750,  5.000) = 40219 
    [ 5.000,  6.250) = 2423 
    [ 6.250,  7.500) = 2287 
    [ 7.500,  8.750) = 848 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 85 
    [11.250, 12.500) = 186 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 103 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.725 ms/op
     p(99.9900) =     17.798 ms/op
     p(99.9990) =     19.819 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.903 ± 3.685  ops/ms
ClientPb.existUser                       thrpt       3  10.449 ± 4.033  ops/ms
ClientPb.getUser                         thrpt       3   9.883 ± 0.318  ops/ms
ClientPb.listUser                        thrpt       3   8.526 ± 1.388  ops/ms
ClientPb.createUser                       avgt       3   3.182 ± 0.695   ms/op
ClientPb.existUser                        avgt       3   3.093 ± 1.346   ms/op
ClientPb.getUser                          avgt       3   3.188 ± 1.370   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 1.478   ms/op
ClientPb.createUser                     sample  294300   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.076           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.823           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.925           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.395           ms/op
ClientPb.existUser                      sample  314138   3.055 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.912           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.186           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.728           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.148           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.214           ms/op
ClientPb.getUser                        sample  293189   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.998           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.047           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.099           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.117           ms/op
ClientPb.listUser                       sample  259273   3.703 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.701           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.725           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.857           ms/op
