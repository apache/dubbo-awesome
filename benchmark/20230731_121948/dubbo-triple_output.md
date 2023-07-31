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
# Warmup Iteration   1: 1.838 ops/ms
# Warmup Iteration   2: 5.678 ops/ms
# Warmup Iteration   3: 8.644 ops/ms
Iteration   1: 9.198 ops/ms
Iteration   2: 9.135 ops/ms
Iteration   3: 9.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.178 ±(99.9%) 0.676 ops/ms [Average]
  (min, avg, max) = (9.135, 9.178, 9.200), stdev = 0.037
  CI (99.9%): [8.502, 9.854] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ops/ms
# Warmup Iteration   2: 8.785 ops/ms
# Warmup Iteration   3: 9.258 ops/ms
Iteration   1: 9.485 ops/ms
Iteration   2: 9.348 ops/ms
Iteration   3: 9.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.421 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (9.348, 9.421, 9.485), stdev = 0.069
  CI (99.9%): [8.163, 10.679] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.503 ops/ms
# Warmup Iteration   2: 8.033 ops/ms
# Warmup Iteration   3: 9.133 ops/ms
Iteration   1: 9.164 ops/ms
Iteration   2: 9.350 ops/ms
Iteration   3: 8.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.123 ±(99.9%) 4.543 ops/ms [Average]
  (min, avg, max) = (8.856, 9.123, 9.350), stdev = 0.249
  CI (99.9%): [4.580, 13.667] (assumes normal distribution)


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
# Warmup Iteration   1: 2.804 ops/ms
# Warmup Iteration   2: 6.643 ops/ms
# Warmup Iteration   3: 7.656 ops/ms
Iteration   1: 7.516 ops/ms
Iteration   2: 7.484 ops/ms
Iteration   3: 7.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.551 ±(99.9%) 1.622 ops/ms [Average]
  (min, avg, max) = (7.484, 7.551, 7.652), stdev = 0.089
  CI (99.9%): [5.929, 9.173] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 9.728 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.922 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.698 ±(99.9%) 0.005 ms/op
Iteration   1: 3.555 ±(99.9%) 0.008 ms/op
Iteration   2: 3.461 ±(99.9%) 0.006 ms/op
Iteration   3: 3.504 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.507 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.461, 3.507, 3.555), stdev = 0.047
  CI (99.9%): [2.651, 4.362] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.474 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.012 ms/op
Iteration   1: 3.261 ±(99.9%) 0.012 ms/op
Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
Iteration   3: 3.377 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.394 ±(99.9%) 2.618 ms/op [Average]
  (min, avg, max) = (3.261, 3.394, 3.546), stdev = 0.143
  CI (99.9%): [0.777, 6.012] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.012 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.773 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.007 ms/op
Iteration   1: 3.507 ±(99.9%) 0.009 ms/op
Iteration   2: 3.512 ±(99.9%) 0.009 ms/op
Iteration   3: 3.434 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.485 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.434, 3.485, 3.512), stdev = 0.044
  CI (99.9%): [2.683, 4.286] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.752 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.011 ms/op
Iteration   1: 4.155 ±(99.9%) 0.012 ms/op
Iteration   2: 3.971 ±(99.9%) 0.015 ms/op
Iteration   3: 4.047 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.058 ±(99.9%) 1.687 ms/op [Average]
  (min, avg, max) = (3.971, 4.058, 4.155), stdev = 0.092
  CI (99.9%): [2.371, 5.745] (assumes normal distribution)


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
# Warmup Iteration   1: 10.395 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.014 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   6.454 ms/op
                 createUser·p0.999:  21.534 ms/op
                 createUser·p0.9999: 25.877 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 3.494 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  23.383 ms/op
                 createUser·p0.9999: 27.066 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   3: 3.431 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.219 ms/op
                 createUser·p0.999:  23.066 ms/op
                 createUser·p0.9999: 34.801 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277614
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7623 
    [ 2.500,  5.000) = 262382 
    [ 5.000,  7.500) = 6458 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 57 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.797 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 9.956 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.009 ms/op
Iteration   1: 3.363 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  11.796 ms/op
                 existUser·p0.9999: 23.298 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.270 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  15.969 ms/op
                 existUser·p0.9999: 36.715 ms/op
                 existUser·p1.00:   37.945 ms/op

Iteration   3: 3.433 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  20.464 ms/op
                 existUser·p0.9999: 25.102 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286160
  mean =      3.354 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10824 
    [ 2.500,  5.000) = 270355 
    [ 5.000,  7.500) = 4261 
    [ 7.500, 10.000) = 219 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     15.445 ms/op
     p(99.9900) =     35.677 ms/op
     p(99.9990) =     37.428 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.277 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
Iteration   1: 3.551 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  21.549 ms/op
                 getUser·p0.9999: 26.836 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   2: 3.459 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.743 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  10.398 ms/op
                 getUser·p0.9999: 24.398 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.566 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.667 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 28.215 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272218
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4080 
    [ 2.500,  5.000) = 260125 
    [ 5.000,  7.500) = 6736 
    [ 7.500, 10.000) = 877 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      1.667 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     26.928 ms/op
     p(99.9990) =     28.881 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 10.715 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.557 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.014 ms/op
Iteration   1: 4.146 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   4.006 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.331 ms/op
                 listUser·p0.999:  22.541 ms/op
                 listUser·p0.9999: 24.946 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.109 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  16.535 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   3: 4.078 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   6.925 ms/op
                 listUser·p0.999:  14.615 ms/op
                 listUser·p0.9999: 15.649 ms/op
                 listUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233248
  mean =      4.111 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 224819 
    [ 5.000,  7.500) = 6097 
    [ 7.500, 10.000) = 1267 
    [10.000, 12.500) = 464 
    [12.500, 15.000) = 246 
    [15.000, 17.500) = 188 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     15.905 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.178 ± 0.676  ops/ms
ClientPb.existUser                       thrpt       3   9.421 ± 1.258  ops/ms
ClientPb.getUser                         thrpt       3   9.123 ± 4.543  ops/ms
ClientPb.listUser                        thrpt       3   7.551 ± 1.622  ops/ms
ClientPb.createUser                       avgt       3   3.507 ± 0.855   ms/op
ClientPb.existUser                        avgt       3   3.394 ± 2.618   ms/op
ClientPb.getUser                          avgt       3   3.485 ± 0.801   ms/op
ClientPb.listUser                         avgt       3   4.058 ± 1.687   ms/op
ClientPb.createUser                     sample  277614   3.456 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.368           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.348           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.144           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  286160   3.354 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.695           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.445           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.677           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.945           ms/op
ClientPb.getUser                        sample  272218   3.525 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.667           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.428           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.928           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.284           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.472           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.451           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.928           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  233248   4.111 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.134           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.905           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.412           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
