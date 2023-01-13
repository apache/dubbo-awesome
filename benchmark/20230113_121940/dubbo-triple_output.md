# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 6.671 ops/ms
# Warmup Iteration   3: 9.107 ops/ms
Iteration   1: 10.171 ops/ms
Iteration   2: 10.215 ops/ms
Iteration   3: 10.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.237 ±(99.9%) 1.439 ops/ms [Average]
  (min, avg, max) = (10.171, 10.237, 10.324), stdev = 0.079
  CI (99.9%): [8.798, 11.676] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.487 ops/ms
# Warmup Iteration   2: 9.475 ops/ms
# Warmup Iteration   3: 9.648 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 9.876 ops/ms
Iteration   3: 10.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.128 ±(99.9%) 4.030 ops/ms [Average]
  (min, avg, max) = (9.876, 10.128, 10.287), stdev = 0.221
  CI (99.9%): [6.098, 14.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ops/ms
# Warmup Iteration   2: 9.347 ops/ms
# Warmup Iteration   3: 9.430 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 9.903 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.974 ±(99.9%) 4.123 ops/ms [Average]
  (min, avg, max) = (9.793, 9.974, 10.227), stdev = 0.226
  CI (99.9%): [5.851, 14.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.017 ops/ms
# Warmup Iteration   2: 7.691 ops/ms
# Warmup Iteration   3: 8.063 ops/ms
Iteration   1: 8.826 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.563 ±(99.9%) 4.515 ops/ms [Average]
  (min, avg, max) = (8.335, 8.563, 8.826), stdev = 0.247
  CI (99.9%): [4.048, 13.078] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.290 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.313 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.002 ms/op
Iteration   2: 3.131 ±(99.9%) 0.005 ms/op
Iteration   3: 3.147 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.167 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.131, 3.167, 3.224), stdev = 0.050
  CI (99.9%): [2.260, 4.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.859 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.003 ms/op
Iteration   1: 3.091 ±(99.9%) 0.008 ms/op
Iteration   2: 3.046 ±(99.9%) 0.001 ms/op
Iteration   3: 3.018 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.052 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.018, 3.052, 3.091), stdev = 0.037
  CI (99.9%): [2.377, 3.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.037 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.463 ±(99.9%) 0.004 ms/op
Iteration   1: 3.233 ±(99.9%) 0.007 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.351 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.258 ±(99.9%) 1.533 ms/op [Average]
  (min, avg, max) = (3.189, 3.258, 3.351), stdev = 0.084
  CI (99.9%): [1.725, 4.790] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.658 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.009 ms/op
Iteration   1: 3.805 ±(99.9%) 0.005 ms/op
Iteration   2: 3.666 ±(99.9%) 0.010 ms/op
Iteration   3: 3.729 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.733 ±(99.9%) 1.264 ms/op [Average]
  (min, avg, max) = (3.666, 3.733, 3.805), stdev = 0.069
  CI (99.9%): [2.469, 4.997] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.938 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.474 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.118 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.358 ms/op
                 createUser·p0.999:  11.786 ms/op
                 createUser·p0.9999: 21.721 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.194 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.338 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  17.018 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303061
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18171 
    [ 2.500,  5.000) = 280256 
    [ 5.000,  7.500) = 3755 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     16.062 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.135 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  12.745 ms/op
                 existUser·p0.9999: 19.811 ms/op
                 existUser·p1.00:   20.840 ms/op

Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 24.664 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  14.631 ms/op
                 existUser·p0.9999: 25.753 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304235
  mean =      3.153 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27389 
    [ 2.500,  5.000) = 271293 
    [ 5.000,  7.500) = 4844 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.986 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.010 ms/op
Iteration   1: 3.312 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.351 ms/op
                 getUser·p0.999:  13.549 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.885 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  10.535 ms/op
                 getUser·p0.9999: 22.871 ms/op
                 getUser·p1.00:   23.233 ms/op

Iteration   3: 3.454 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  15.416 ms/op
                 getUser·p0.9999: 22.307 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289611
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16190 
    [ 2.500,  5.000) = 264477 
    [ 5.000,  7.500) = 8111 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.115 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.175 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.779 ±(99.9%) 0.012 ms/op
Iteration   1: 3.810 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.305 ms/op
                 listUser·p0.999:  14.144 ms/op
                 listUser·p0.9999: 19.451 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 3.760 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.182 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  13.566 ms/op
                 listUser·p0.9999: 15.827 ms/op
                 listUser·p1.00:   15.892 ms/op

Iteration   3: 3.836 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.550 ms/op
                 listUser·p0.999:  12.363 ms/op
                 listUser·p0.9999: 18.491 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252380
  mean =      3.802 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 87 
    [ 2.500,  3.750) = 181732 
    [ 3.750,  5.000) = 60090 
    [ 5.000,  6.250) = 4460 
    [ 6.250,  7.500) = 3938 
    [ 7.500,  8.750) = 1046 
    [ 8.750, 10.000) = 335 
    [10.000, 11.250) = 150 
    [11.250, 12.500) = 199 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     13.410 ms/op
     p(99.9900) =     19.063 ms/op
     p(99.9990) =     19.803 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.237 ± 1.439  ops/ms
ClientPb.existUser                       thrpt       3  10.128 ± 4.030  ops/ms
ClientPb.getUser                         thrpt       3   9.974 ± 4.123  ops/ms
ClientPb.listUser                        thrpt       3   8.563 ± 4.515  ops/ms
ClientPb.createUser                       avgt       3   3.167 ± 0.908   ms/op
ClientPb.existUser                        avgt       3   3.052 ± 0.675   ms/op
ClientPb.getUser                          avgt       3   3.258 ± 1.533   ms/op
ClientPb.listUser                         avgt       3   3.733 ± 1.264   ms/op
ClientPb.createUser                     sample  303061   3.167 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.580           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.871           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.062           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.643           ms/op
ClientPb.existUser                      sample  304235   3.153 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.400           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.822           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.516           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.166           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.182           ms/op
ClientPb.getUser                        sample  289611   3.314 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.120           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.829           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.856           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.233           ms/op
ClientPb.listUser                       sample  252380   3.802 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.030           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.674           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.410           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.063           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.956           ms/op
