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
# Warmup Iteration   1: 2.065 ops/ms
# Warmup Iteration   2: 5.716 ops/ms
# Warmup Iteration   3: 8.759 ops/ms
Iteration   1: 9.523 ops/ms
Iteration   2: 9.583 ops/ms
Iteration   3: 9.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.547 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (9.523, 9.547, 9.583), stdev = 0.032
  CI (99.9%): [8.960, 10.134] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.017 ops/ms
# Warmup Iteration   2: 8.651 ops/ms
# Warmup Iteration   3: 9.528 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 9.997 ops/ms
Iteration   3: 9.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.920 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (9.853, 9.920, 9.997), stdev = 0.072
  CI (99.9%): [8.599, 11.242] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.929 ops/ms
# Warmup Iteration   2: 8.569 ops/ms
# Warmup Iteration   3: 8.967 ops/ms
Iteration   1: 9.495 ops/ms
Iteration   2: 9.464 ops/ms
Iteration   3: 9.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.569 ±(99.9%) 2.847 ops/ms [Average]
  (min, avg, max) = (9.464, 9.569, 9.748), stdev = 0.156
  CI (99.9%): [6.722, 12.416] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.658 ops/ms
# Warmup Iteration   2: 6.997 ops/ms
# Warmup Iteration   3: 8.139 ops/ms
Iteration   1: 8.090 ops/ms
Iteration   2: 8.152 ops/ms
Iteration   3: 7.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.060 ±(99.9%) 2.006 ops/ms [Average]
  (min, avg, max) = (7.939, 8.060, 8.152), stdev = 0.110
  CI (99.9%): [6.054, 10.066] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.101 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.004 ms/op
Iteration   1: 3.402 ±(99.9%) 0.011 ms/op
Iteration   2: 3.374 ±(99.9%) 0.009 ms/op
Iteration   3: 3.504 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.427 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (3.374, 3.427, 3.504), stdev = 0.068
  CI (99.9%): [2.179, 4.675] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.141 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
Iteration   1: 3.299 ±(99.9%) 0.009 ms/op
Iteration   2: 3.223 ±(99.9%) 0.009 ms/op
Iteration   3: 3.201 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.241 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.201, 3.241, 3.299), stdev = 0.051
  CI (99.9%): [2.303, 4.180] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.066 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.673 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.005 ms/op
Iteration   1: 3.362 ±(99.9%) 0.007 ms/op
Iteration   2: 3.501 ±(99.9%) 0.003 ms/op
Iteration   3: 3.440 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.434 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (3.362, 3.434, 3.501), stdev = 0.070
  CI (99.9%): [2.163, 4.705] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.015 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
Iteration   1: 3.991 ±(99.9%) 0.014 ms/op
Iteration   2: 3.886 ±(99.9%) 0.014 ms/op
Iteration   3: 3.898 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.925 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.886, 3.925, 3.991), stdev = 0.058
  CI (99.9%): [2.874, 4.976] (assumes normal distribution)


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
# Warmup Iteration   1: 9.959 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.818 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.426 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  18.021 ms/op
                 createUser·p0.9999: 21.059 ms/op
                 createUser·p1.00:   21.332 ms/op

Iteration   2: 3.394 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  19.380 ms/op
                 createUser·p0.9999: 22.995 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.433 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.615 ms/op
                 createUser·p0.999:  17.332 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280585
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11815 
    [ 2.500,  5.000) = 262590 
    [ 5.000,  7.500) = 5170 
    [ 7.500, 10.000) = 626 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.081 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.512 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 8.141 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
Iteration   1: 3.235 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  8.984 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   2: 3.334 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.718 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  9.896 ms/op
                 existUser·p0.9999: 24.229 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   3: 3.279 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.023 ms/op
                 existUser·p0.999:  14.026 ms/op
                 existUser·p0.9999: 26.444 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292214
  mean =      3.282 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9992 
    [ 2.500,  5.000) = 278319 
    [ 5.000,  7.500) = 2922 
    [ 7.500, 10.000) = 666 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     11.222 ms/op
     p(99.9900) =     25.191 ms/op
     p(99.9990) =     26.744 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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
# Warmup Iteration   1: 8.884 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.012 ms/op
Iteration   1: 3.529 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  9.306 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 3.454 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  21.836 ms/op
                 getUser·p0.9999: 37.880 ms/op
                 getUser·p1.00:   38.535 ms/op

Iteration   3: 3.379 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   5.820 ms/op
                 getUser·p0.999:  21.979 ms/op
                 getUser·p0.9999: 28.264 ms/op
                 getUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277810
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7926 
    [ 2.500,  5.000) = 263320 
    [ 5.000,  7.500) = 5715 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.315 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     37.325 ms/op
     p(99.9990) =     38.339 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


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
# Warmup Iteration   1: 10.445 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.012 ms/op
Iteration   1: 4.042 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.264 ms/op
                 listUser·p0.999:  15.706 ms/op
                 listUser·p0.9999: 33.691 ms/op
                 listUser·p1.00:   37.159 ms/op

Iteration   2: 4.159 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 21.909 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 3.890 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.169 ms/op
                 listUser·p0.999:  14.284 ms/op
                 listUser·p0.9999: 16.380 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238244
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 229941 
    [ 5.000,  7.500) = 5996 
    [ 7.500, 10.000) = 1442 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     32.539 ms/op
     p(99.9990) =     34.094 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.547 ± 0.587  ops/ms
ClientPb.existUser                       thrpt       3   9.920 ± 1.322  ops/ms
ClientPb.getUser                         thrpt       3   9.569 ± 2.847  ops/ms
ClientPb.listUser                        thrpt       3   8.060 ± 2.006  ops/ms
ClientPb.createUser                       avgt       3   3.427 ± 1.248   ms/op
ClientPb.existUser                        avgt       3   3.241 ± 0.939   ms/op
ClientPb.getUser                          avgt       3   3.434 ± 1.271   ms/op
ClientPb.listUser                         avgt       3   3.925 ± 1.051   ms/op
ClientPb.createUser                     sample  280585   3.418 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.081           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.512           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.099           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.082           ms/op
ClientPb.existUser                      sample  292214   3.282 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.573           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.222           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  277810   3.453 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.671           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.315           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.075           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.325           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.535           ms/op
ClientPb.listUser                       sample  238244   4.027 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.425           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.414           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.958           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.539           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.159           ms/op
