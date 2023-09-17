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
# Warmup Iteration   1: 1.868 ops/ms
# Warmup Iteration   2: 5.469 ops/ms
# Warmup Iteration   3: 8.372 ops/ms
Iteration   1: 9.165 ops/ms
Iteration   2: 9.287 ops/ms
Iteration   3: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.208 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (9.165, 9.208, 9.287), stdev = 0.068
  CI (99.9%): [7.968, 10.449] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.502 ops/ms
# Warmup Iteration   2: 9.046 ops/ms
# Warmup Iteration   3: 9.545 ops/ms
Iteration   1: 9.245 ops/ms
Iteration   2: 9.719 ops/ms
Iteration   3: 9.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.529 ±(99.9%) 4.573 ops/ms [Average]
  (min, avg, max) = (9.245, 9.529, 9.719), stdev = 0.251
  CI (99.9%): [4.956, 14.102] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.763 ops/ms
# Warmup Iteration   2: 7.991 ops/ms
# Warmup Iteration   3: 8.730 ops/ms
Iteration   1: 9.246 ops/ms
Iteration   2: 9.295 ops/ms
Iteration   3: 9.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.291 ±(99.9%) 0.784 ops/ms [Average]
  (min, avg, max) = (9.246, 9.291, 9.332), stdev = 0.043
  CI (99.9%): [8.507, 10.075] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.580 ops/ms
# Warmup Iteration   2: 6.985 ops/ms
# Warmup Iteration   3: 7.775 ops/ms
Iteration   1: 7.741 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 7.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.794 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (7.707, 7.794, 7.934), stdev = 0.123
  CI (99.9%): [5.555, 10.033] (assumes normal distribution)


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
# Warmup Iteration   1: 10.387 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.005 ms/op
Iteration   1: 3.486 ±(99.9%) 0.007 ms/op
Iteration   2: 3.408 ±(99.9%) 0.006 ms/op
Iteration   3: 3.440 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.445 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (3.408, 3.445, 3.486), stdev = 0.039
  CI (99.9%): [2.726, 4.164] (assumes normal distribution)


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
# Warmup Iteration   1: 10.556 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.003 ms/op
Iteration   1: 3.279 ±(99.9%) 0.005 ms/op
Iteration   2: 3.339 ±(99.9%) 0.005 ms/op
Iteration   3: 3.279 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.299 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.279, 3.299, 3.339), stdev = 0.035
  CI (99.9%): [2.668, 3.930] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.726 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.004 ms/op
Iteration   1: 3.397 ±(99.9%) 0.005 ms/op
Iteration   2: 3.439 ±(99.9%) 0.008 ms/op
Iteration   3: 3.553 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.463 ±(99.9%) 1.467 ms/op [Average]
  (min, avg, max) = (3.397, 3.463, 3.553), stdev = 0.080
  CI (99.9%): [1.996, 4.930] (assumes normal distribution)


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
# Warmup Iteration   1: 10.622 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.008 ms/op
Iteration   1: 4.065 ±(99.9%) 0.008 ms/op
Iteration   2: 4.105 ±(99.9%) 0.007 ms/op
Iteration   3: 4.015 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.062 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (4.015, 4.062, 4.105), stdev = 0.045
  CI (99.9%): [3.240, 4.883] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.087 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.578 ±(99.9%) 0.009 ms/op
Iteration   1: 3.531 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  20.644 ms/op
                 createUser·p0.9999: 22.606 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   2: 3.518 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.676 ms/op
                 createUser·p0.999:  21.711 ms/op
                 createUser·p0.9999: 26.638 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   3: 3.367 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.518 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.063 ms/op
                 createUser·p0.999:  18.514 ms/op
                 createUser·p0.9999: 26.117 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276327
  mean =      3.471 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5812 
    [ 2.500,  5.000) = 265613 
    [ 5.000,  7.500) = 3996 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 149 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     19.912 ms/op
     p(99.9900) =     25.887 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 7.248 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.423 ms/op
                 existUser·p0.999:  12.697 ms/op
                 existUser·p0.9999: 22.334 ms/op
                 existUser·p1.00:   22.610 ms/op

Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.016 ms/op
                 existUser·p0.999:  21.175 ms/op
                 existUser·p0.9999: 28.298 ms/op
                 existUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283298
  mean =      3.386 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6524 
    [ 2.500,  5.000) = 269817 
    [ 5.000,  7.500) = 6018 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.006 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     26.335 ms/op
     p(99.9990) =     28.694 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 9.638 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.579 ±(99.9%) 0.009 ms/op
Iteration   1: 3.651 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.374 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  20.048 ms/op
                 getUser·p0.9999: 22.454 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.444 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  22.626 ms/op
                 getUser·p0.9999: 24.768 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.528 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  18.711 ms/op
                 getUser·p0.9999: 26.045 ms/op
                 getUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271011
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5830 
    [ 2.500,  5.000) = 256718 
    [ 5.000,  7.500) = 7160 
    [ 7.500, 10.000) = 728 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     19.529 ms/op
     p(99.9900) =     25.303 ms/op
     p(99.9990) =     26.571 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 10.566 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.013 ms/op
Iteration   1: 4.120 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  17.517 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 4.156 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  15.256 ms/op
                 listUser·p0.9999: 17.934 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.015 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  14.242 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234378
  mean =      4.096 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 83 
    [ 2.500,  5.000) = 226379 
    [ 5.000,  7.500) = 6525 
    [ 7.500, 10.000) = 685 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.969 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.133 ms/op
     p(99.9900) =     22.577 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.208 ± 1.241  ops/ms
ClientPb.existUser                       thrpt       3   9.529 ± 4.573  ops/ms
ClientPb.getUser                         thrpt       3   9.291 ± 0.784  ops/ms
ClientPb.listUser                        thrpt       3   7.794 ± 2.239  ops/ms
ClientPb.createUser                       avgt       3   3.445 ± 0.719   ms/op
ClientPb.existUser                        avgt       3   3.299 ± 0.631   ms/op
ClientPb.getUser                          avgt       3   3.463 ± 1.467   ms/op
ClientPb.listUser                         avgt       3   4.062 ± 0.822   ms/op
ClientPb.createUser                     sample  276327   3.471 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.059           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.235           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.677           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.912           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.887           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.804           ms/op
ClientPb.existUser                      sample  283298   3.386 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.006           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.335           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  271011   3.539 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.274           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.404           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.808           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.529           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.303           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.197           ms/op
ClientPb.listUser                       sample  234378   4.096 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.913           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.133           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.577           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
