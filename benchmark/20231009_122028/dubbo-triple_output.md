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
# Warmup Iteration   1: 1.548 ops/ms
# Warmup Iteration   2: 4.032 ops/ms
# Warmup Iteration   3: 7.862 ops/ms
Iteration   1: 8.087 ops/ms
Iteration   2: 8.426 ops/ms
Iteration   3: 8.665 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.393 ±(99.9%) 5.305 ops/ms [Average]
  (min, avg, max) = (8.087, 8.393, 8.665), stdev = 0.291
  CI (99.9%): [3.088, 13.698] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.455 ops/ms
# Warmup Iteration   2: 7.772 ops/ms
# Warmup Iteration   3: 9.046 ops/ms
Iteration   1: 9.163 ops/ms
Iteration   2: 9.080 ops/ms
Iteration   3: 9.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.179 ±(99.9%) 1.954 ops/ms [Average]
  (min, avg, max) = (9.080, 9.179, 9.293), stdev = 0.107
  CI (99.9%): [7.225, 11.132] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.215 ops/ms
# Warmup Iteration   2: 7.651 ops/ms
# Warmup Iteration   3: 8.881 ops/ms
Iteration   1: 8.768 ops/ms
Iteration   2: 9.059 ops/ms
Iteration   3: 8.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.894 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (8.768, 8.894, 9.059), stdev = 0.149
  CI (99.9%): [6.173, 11.615] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.387 ops/ms
# Warmup Iteration   2: 6.360 ops/ms
# Warmup Iteration   3: 7.346 ops/ms
Iteration   1: 7.409 ops/ms
Iteration   2: 7.511 ops/ms
Iteration   3: 7.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.492 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (7.409, 7.492, 7.557), stdev = 0.075
  CI (99.9%): [6.116, 8.869] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 11.292 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 4.030 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.004 ms/op
Iteration   1: 3.738 ±(99.9%) 0.006 ms/op
Iteration   2: 3.606 ±(99.9%) 0.004 ms/op
Iteration   3: 3.595 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.646 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (3.595, 3.646, 3.738), stdev = 0.079
  CI (99.9%): [2.199, 5.093] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.925 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.004 ms/op
Iteration   1: 3.450 ±(99.9%) 0.006 ms/op
Iteration   2: 3.513 ±(99.9%) 0.006 ms/op
Iteration   3: 3.361 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.441 ±(99.9%) 1.392 ms/op [Average]
  (min, avg, max) = (3.361, 3.441, 3.513), stdev = 0.076
  CI (99.9%): [2.049, 4.833] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.039 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.799 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.586 ±(99.9%) 0.005 ms/op
Iteration   1: 3.538 ±(99.9%) 0.004 ms/op
Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
Iteration   3: 3.529 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.537 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (3.529, 3.537, 3.546), stdev = 0.009
  CI (99.9%): [3.382, 3.693] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.887 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.824 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.354 ±(99.9%) 0.005 ms/op
Iteration   1: 4.294 ±(99.9%) 0.011 ms/op
Iteration   2: 4.285 ±(99.9%) 0.007 ms/op
Iteration   3: 4.225 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.268 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (4.225, 4.268, 4.294), stdev = 0.037
  CI (99.9%): [3.586, 4.949] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.899 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.017 ms/op
Iteration   1: 3.656 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.153 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  22.875 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   2: 3.596 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.290 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.431 ms/op
                 createUser·p0.99:   7.430 ms/op
                 createUser·p0.999:  25.002 ms/op
                 createUser·p0.9999: 26.345 ms/op
                 createUser·p1.00:   26.903 ms/op

Iteration   3: 3.657 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.461 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  24.818 ms/op
                 createUser·p0.9999: 29.434 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264009
  mean =      3.636 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5112 
    [ 2.500,  5.000) = 248857 
    [ 5.000,  7.500) = 7154 
    [ 7.500, 10.000) = 1974 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 160 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     23.756 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     30.114 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 10.296 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.012 ms/op
Iteration   1: 3.431 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  10.201 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   25.231 ms/op

Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   7.471 ms/op
                 existUser·p0.999:  22.785 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.472 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.260 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.225 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  25.293 ms/op
                 existUser·p0.9999: 29.058 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277148
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7209 
    [ 2.500,  5.000) = 261059 
    [ 5.000,  7.500) = 6744 
    [ 7.500, 10.000) = 1465 
    [10.000, 12.500) = 317 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 108 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     14.940 ms/op
     p(99.9900) =     27.422 ms/op
     p(99.9990) =     29.926 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 11.350 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.014 ms/op
Iteration   1: 3.650 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.229 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  22.599 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.610 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  14.488 ms/op
                 getUser·p0.9999: 26.018 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   3: 3.662 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   3.498 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   7.487 ms/op
                 getUser·p0.999:  26.892 ms/op
                 getUser·p0.9999: 29.524 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 263574
  mean =      3.641 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2552 
    [ 2.500,  5.000) = 250044 
    [ 5.000,  7.500) = 7919 
    [ 7.500, 10.000) = 2097 
    [10.000, 12.500) = 385 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     20.513 ms/op
     p(99.9900) =     28.274 ms/op
     p(99.9990) =     30.096 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 12.062 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.854 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.018 ms/op
Iteration   1: 4.374 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  24.377 ms/op
                 listUser·p0.9999: 31.208 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   2: 4.306 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  17.719 ms/op
                 listUser·p0.9999: 20.654 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.360 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 24.858 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 220705
  mean =      4.346 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 146 
    [ 2.500,  5.000) = 206259 
    [ 5.000,  7.500) = 9554 
    [ 7.500, 10.000) = 3452 
    [10.000, 12.500) = 525 
    [12.500, 15.000) = 257 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      4.149 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      8.847 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     27.621 ms/op
     p(99.9990) =     31.582 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.393 ± 5.305  ops/ms
ClientPb.existUser                       thrpt       3   9.179 ± 1.954  ops/ms
ClientPb.getUser                         thrpt       3   8.894 ± 2.721  ops/ms
ClientPb.listUser                        thrpt       3   7.492 ± 1.377  ops/ms
ClientPb.createUser                       avgt       3   3.646 ± 1.447   ms/op
ClientPb.existUser                        avgt       3   3.441 ± 1.392   ms/op
ClientPb.getUser                          avgt       3   3.537 ± 0.156   ms/op
ClientPb.listUser                         avgt       3   4.268 ± 0.681   ms/op
ClientPb.createUser                     sample  264009   3.636 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.290           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.756           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.344           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.212           ms/op
ClientPb.existUser                      sample  277148   3.463 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.233           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.209           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.940           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.422           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  263574   3.641 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.229           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.692           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.513           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.274           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  220705   4.346 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.235           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.847           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.579           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.621           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.621           ms/op
