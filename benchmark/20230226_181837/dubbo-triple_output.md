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
# Warmup Iteration   1: 2.644 ops/ms
# Warmup Iteration   2: 5.882 ops/ms
# Warmup Iteration   3: 9.329 ops/ms
Iteration   1: 9.521 ops/ms
Iteration   2: 10.028 ops/ms
Iteration   3: 9.899 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.816 ±(99.9%) 4.803 ops/ms [Average]
  (min, avg, max) = (9.521, 9.816, 10.028), stdev = 0.263
  CI (99.9%): [5.013, 14.619] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.239 ops/ms
# Warmup Iteration   2: 9.679 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 9.952 ops/ms
Iteration   2: 10.877 ops/ms
Iteration   3: 10.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.508 ±(99.9%) 8.945 ops/ms [Average]
  (min, avg, max) = (9.952, 10.508, 10.877), stdev = 0.490
  CI (99.9%): [1.563, 19.453] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.580 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 9.705 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 10.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.184 ±(99.9%) 5.423 ops/ms [Average]
  (min, avg, max) = (9.921, 10.184, 10.506), stdev = 0.297
  CI (99.9%): [4.761, 15.606] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.205 ops/ms
# Warmup Iteration   2: 7.481 ops/ms
# Warmup Iteration   3: 8.602 ops/ms
Iteration   1: 8.611 ops/ms
Iteration   2: 8.528 ops/ms
Iteration   3: 8.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.545 ±(99.9%) 1.100 ops/ms [Average]
  (min, avg, max) = (8.494, 8.545, 8.611), stdev = 0.060
  CI (99.9%): [7.444, 9.645] (assumes normal distribution)


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
# Warmup Iteration   1: 8.775 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.007 ms/op
Iteration   1: 3.337 ±(99.9%) 0.004 ms/op
Iteration   2: 3.242 ±(99.9%) 0.006 ms/op
Iteration   3: 3.073 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.217 ±(99.9%) 2.446 ms/op [Average]
  (min, avg, max) = (3.073, 3.217, 3.337), stdev = 0.134
  CI (99.9%): [0.771, 5.663] (assumes normal distribution)


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
# Warmup Iteration   1: 7.183 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
Iteration   1: 3.173 ±(99.9%) 0.005 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.073 ±(99.9%) 1.598 ms/op [Average]
  (min, avg, max) = (3.012, 3.073, 3.173), stdev = 0.088
  CI (99.9%): [1.475, 4.670] (assumes normal distribution)


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
# Warmup Iteration   1: 7.009 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.392 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.005 ms/op
Iteration   1: 3.202 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.005 ms/op
Iteration   3: 3.135 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.157 ±(99.9%) 0.709 ms/op [Average]
  (min, avg, max) = (3.135, 3.157, 3.202), stdev = 0.039
  CI (99.9%): [2.449, 3.866] (assumes normal distribution)


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
# Warmup Iteration   1: 8.930 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.004 ms/op
Iteration   1: 3.744 ±(99.9%) 0.008 ms/op
Iteration   2: 3.747 ±(99.9%) 0.008 ms/op
Iteration   3: 3.652 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.714 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.652, 3.714, 3.747), stdev = 0.054
  CI (99.9%): [2.730, 4.699] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.104 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.010 ms/op
Iteration   1: 3.150 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.423 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 34.790 ms/op
                 createUser·p1.00:   35.062 ms/op

Iteration   2: 3.194 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  10.336 ms/op
                 createUser·p0.9999: 21.463 ms/op
                 createUser·p1.00:   22.544 ms/op

Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.487 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   5.353 ms/op
                 createUser·p0.999:  16.111 ms/op
                 createUser·p0.9999: 28.963 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302339
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15058 
    [ 2.500,  5.000) = 283106 
    [ 5.000,  7.500) = 3315 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     17.356 ms/op
     p(99.9900) =     32.967 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 7.282 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.489 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  16.583 ms/op
                 existUser·p0.9999: 23.733 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.037 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.809 ms/op
                 existUser·p0.999:  17.700 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  18.589 ms/op
                 existUser·p0.9999: 23.574 ms/op
                 existUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315830
  mean =      3.036 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20172 
    [ 2.500,  5.000) = 291130 
    [ 5.000,  7.500) = 3684 
    [ 7.500, 10.000) = 360 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 161 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     17.274 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     26.444 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 7.047 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.012 ms/op
Iteration   1: 3.153 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  8.791 ms/op
                 getUser·p0.9999: 24.440 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  8.476 ms/op
                 getUser·p0.9999: 22.309 ms/op
                 getUser·p1.00:   23.167 ms/op

Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.296 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 20.976 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 303626
  mean =      3.160 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10837 
    [ 2.500,  5.000) = 286575 
    [ 5.000,  7.500) = 5499 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     23.417 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 8.737 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.011 ms/op
Iteration   1: 3.665 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.730 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 16.620 ms/op
                 listUser·p1.00:   16.663 ms/op

Iteration   3: 3.687 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 19.344 ms/op
                 listUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259697
  mean =      3.694 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 253618 
    [ 5.000,  7.500) = 4320 
    [ 7.500, 10.000) = 1082 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.925 ms/op
     p(99.9900) =     20.383 ms/op
     p(99.9990) =     22.047 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.816 ± 4.803  ops/ms
ClientPb.existUser                       thrpt       3  10.508 ± 8.945  ops/ms
ClientPb.getUser                         thrpt       3  10.184 ± 5.423  ops/ms
ClientPb.listUser                        thrpt       3   8.545 ± 1.100  ops/ms
ClientPb.createUser                       avgt       3   3.217 ± 2.446   ms/op
ClientPb.existUser                        avgt       3   3.073 ± 1.598   ms/op
ClientPb.getUser                          avgt       3   3.157 ± 0.709   ms/op
ClientPb.listUser                         avgt       3   3.714 ± 0.984   ms/op
ClientPb.createUser                     sample  302339   3.172 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.465           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.356           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.967           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  315830   3.036 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.934           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.274           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.150           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  303626   3.160 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.527           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.513           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.486           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.417           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.083           ms/op
ClientPb.listUser                       sample  259697   3.694 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.564           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.742           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.383           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.691           ms/op
