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
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 5.305 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 8.810 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.156 ±(99.9%) 5.488 ops/ms [Average]
  (min, avg, max) = (8.810, 9.156, 9.348), stdev = 0.301
  CI (99.9%): [3.669, 14.644] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 9.150 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 9.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.837 ±(99.9%) 4.549 ops/ms [Average]
  (min, avg, max) = (9.621, 9.837, 10.110), stdev = 0.249
  CI (99.9%): [5.288, 14.385] (assumes normal distribution)


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
# Warmup Iteration   1: 2.818 ops/ms
# Warmup Iteration   2: 8.285 ops/ms
# Warmup Iteration   3: 8.919 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.640 ops/ms
Iteration   3: 9.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.451 ±(99.9%) 3.386 ops/ms [Average]
  (min, avg, max) = (9.269, 9.451, 9.640), stdev = 0.186
  CI (99.9%): [6.066, 12.837] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.759 ops/ms
# Warmup Iteration   2: 6.817 ops/ms
# Warmup Iteration   3: 7.627 ops/ms
Iteration   1: 7.776 ops/ms
Iteration   2: 7.977 ops/ms
Iteration   3: 7.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.859 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (7.776, 7.859, 7.977), stdev = 0.105
  CI (99.9%): [5.945, 9.774] (assumes normal distribution)


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
# Warmup Iteration   1: 9.278 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.009 ms/op
Iteration   1: 3.617 ±(99.9%) 0.007 ms/op
Iteration   2: 3.396 ±(99.9%) 0.008 ms/op
Iteration   3: 3.484 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.499 ±(99.9%) 2.025 ms/op [Average]
  (min, avg, max) = (3.396, 3.499, 3.617), stdev = 0.111
  CI (99.9%): [1.473, 5.524] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.389 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.005 ms/op
Iteration   1: 3.213 ±(99.9%) 0.011 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.271 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.256 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (3.213, 3.256, 3.284), stdev = 0.038
  CI (99.9%): [2.563, 3.949] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.673 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.577 ±(99.9%) 0.006 ms/op
Iteration   1: 3.420 ±(99.9%) 0.009 ms/op
Iteration   2: 3.450 ±(99.9%) 0.005 ms/op
Iteration   3: 3.532 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.467 ±(99.9%) 1.059 ms/op [Average]
  (min, avg, max) = (3.420, 3.467, 3.532), stdev = 0.058
  CI (99.9%): [2.409, 4.526] (assumes normal distribution)


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
# Warmup Iteration   1: 11.580 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.008 ms/op
Iteration   1: 3.886 ±(99.9%) 0.013 ms/op
Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
Iteration   3: 4.000 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.966 ±(99.9%) 1.258 ms/op [Average]
  (min, avg, max) = (3.886, 3.966, 4.010), stdev = 0.069
  CI (99.9%): [2.708, 5.223] (assumes normal distribution)


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
# Warmup Iteration   1: 10.725 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.712 ±(99.9%) 0.014 ms/op
Iteration   1: 3.419 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  21.594 ms/op
                 createUser·p0.9999: 29.260 ms/op
                 createUser·p1.00:   30.212 ms/op

Iteration   2: 3.437 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 25.638 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.436 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.544 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  16.658 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279528
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4275 
    [ 2.500,  5.000) = 269240 
    [ 5.000,  7.500) = 4797 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     27.396 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 8.629 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.393 ±(99.9%) 0.009 ms/op
Iteration   1: 3.273 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  12.591 ms/op
                 existUser·p0.9999: 25.112 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.282 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  13.270 ms/op
                 existUser·p0.9999: 27.087 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  18.296 ms/op
                 existUser·p0.9999: 26.752 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290560
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5430 
    [ 2.500,  5.000) = 279324 
    [ 5.000,  7.500) = 4790 
    [ 7.500, 10.000) = 545 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     13.644 ms/op
     p(99.9900) =     26.507 ms/op
     p(99.9990) =     28.279 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 11.022 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.589 ±(99.9%) 0.010 ms/op
Iteration   1: 3.392 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.305 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.889 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  20.517 ms/op
                 getUser·p0.9999: 24.529 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  22.434 ms/op
                 getUser·p0.9999: 26.573 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 3.446 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.868 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  17.059 ms/op
                 getUser·p0.9999: 25.580 ms/op
                 getUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280451
  mean =      3.420 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 782 
    [ 2.500,  5.000) = 273712 
    [ 5.000,  7.500) = 4778 
    [ 7.500, 10.000) = 663 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 144 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     19.205 ms/op
     p(99.9900) =     25.721 ms/op
     p(99.9990) =     26.751 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 12.395 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.815 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.244 ±(99.9%) 0.014 ms/op
Iteration   1: 4.047 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  21.660 ms/op
                 listUser·p0.9999: 29.164 ms/op
                 listUser·p1.00:   31.293 ms/op

Iteration   2: 4.000 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.630 ms/op
                 listUser·p0.9999: 16.646 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   3: 3.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.919 ms/op
                 listUser·p0.9999: 16.236 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239567
  mean =      4.006 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 231869 
    [ 5.000,  7.500) = 5893 
    [ 7.500, 10.000) = 1105 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     27.264 ms/op
     p(99.9990) =     29.940 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.156 ± 5.488  ops/ms
ClientPb.existUser                       thrpt       3   9.837 ± 4.549  ops/ms
ClientPb.getUser                         thrpt       3   9.451 ± 3.386  ops/ms
ClientPb.listUser                        thrpt       3   7.859 ± 1.915  ops/ms
ClientPb.createUser                       avgt       3   3.499 ± 2.025   ms/op
ClientPb.existUser                        avgt       3   3.256 ± 0.693   ms/op
ClientPb.getUser                          avgt       3   3.467 ± 1.059   ms/op
ClientPb.listUser                         avgt       3   3.966 ± 1.258   ms/op
ClientPb.createUser                     sample  279528   3.431 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.106           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.742           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.396           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  290560   3.301 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.282           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.718           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.644           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.507           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.279           ms/op
ClientPb.getUser                        sample  280451   3.420 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.305           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.293           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.915           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.205           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.721           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  239567   4.006 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.466           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.264           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.293           ms/op
