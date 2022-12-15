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
# Warmup Iteration   1: 1.679 ops/ms
# Warmup Iteration   2: 3.841 ops/ms
# Warmup Iteration   3: 7.524 ops/ms
Iteration   1: 7.706 ops/ms
Iteration   2: 8.557 ops/ms
Iteration   3: 8.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.357 ±(99.9%) 10.541 ops/ms [Average]
  (min, avg, max) = (7.706, 8.357, 8.808), stdev = 0.578
  CI (99.9%): [≈ 0, 18.898] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.514 ops/ms
# Warmup Iteration   2: 7.272 ops/ms
# Warmup Iteration   3: 8.566 ops/ms
Iteration   1: 8.961 ops/ms
Iteration   2: 8.435 ops/ms
Iteration   3: 8.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.784 ±(99.9%) 5.520 ops/ms [Average]
  (min, avg, max) = (8.435, 8.784, 8.961), stdev = 0.303
  CI (99.9%): [3.264, 14.305] (assumes normal distribution)


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
# Warmup Iteration   1: 2.178 ops/ms
# Warmup Iteration   2: 7.333 ops/ms
# Warmup Iteration   3: 8.277 ops/ms
Iteration   1: 8.821 ops/ms
Iteration   2: 8.358 ops/ms
Iteration   3: 8.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.547 ±(99.9%) 4.435 ops/ms [Average]
  (min, avg, max) = (8.358, 8.547, 8.821), stdev = 0.243
  CI (99.9%): [4.112, 12.981] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 6.748 ops/ms
# Warmup Iteration   3: 7.124 ops/ms
Iteration   1: 6.538 ops/ms
Iteration   2: 7.204 ops/ms
Iteration   3: 7.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.079 ±(99.9%) 8.936 ops/ms [Average]
  (min, avg, max) = (6.538, 7.079, 7.493), stdev = 0.490
  CI (99.9%): [≈ 0, 16.015] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.413 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.412 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.004 ms/op
Iteration   1: 4.011 ±(99.9%) 0.010 ms/op
Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
Iteration   3: 3.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.999 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.973, 3.999, 4.013), stdev = 0.023
  CI (99.9%): [3.586, 4.412] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.541 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.701 ±(99.9%) 0.005 ms/op
Iteration   1: 3.767 ±(99.9%) 0.006 ms/op
Iteration   2: 3.701 ±(99.9%) 0.004 ms/op
Iteration   3: 3.429 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.632 ±(99.9%) 3.274 ms/op [Average]
  (min, avg, max) = (3.429, 3.632, 3.767), stdev = 0.179
  CI (99.9%): [0.359, 6.906] (assumes normal distribution)


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
# Warmup Iteration   1: 11.727 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.257 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.004 ms/op
Iteration   1: 3.850 ±(99.9%) 0.008 ms/op
Iteration   2: 3.719 ±(99.9%) 0.011 ms/op
Iteration   3: 3.698 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.756 ±(99.9%) 1.504 ms/op [Average]
  (min, avg, max) = (3.698, 3.756, 3.850), stdev = 0.082
  CI (99.9%): [2.252, 5.260] (assumes normal distribution)


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
# Warmup Iteration   1: 13.840 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.011 ms/op
Iteration   1: 4.788 ±(99.9%) 0.012 ms/op
Iteration   2: 4.346 ±(99.9%) 0.011 ms/op
Iteration   3: 4.244 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.459 ±(99.9%) 5.277 ms/op [Average]
  (min, avg, max) = (4.244, 4.459, 4.788), stdev = 0.289
  CI (99.9%): [≈ 0, 9.737] (assumes normal distribution)


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
# Warmup Iteration   1: 12.183 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.017 ms/op
Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 28.292 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 3.543 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  25.395 ms/op
                 createUser·p0.9999: 31.356 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   3: 3.661 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  22.229 ms/op
                 createUser·p0.9999: 31.604 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263739
  mean =      3.641 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2521 
    [ 2.500,  5.000) = 255042 
    [ 5.000,  7.500) = 4909 
    [ 7.500, 10.000) = 891 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     15.450 ms/op
     p(99.9900) =     31.203 ms/op
     p(99.9990) =     32.240 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 8.932 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
Iteration   1: 3.417 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  21.835 ms/op
                 existUser·p0.9999: 30.766 ms/op
                 existUser·p1.00:   32.637 ms/op

Iteration   2: 3.537 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.266 ms/op
                 existUser·p0.9999: 27.685 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.739 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.358 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  23.968 ms/op
                 existUser·p0.9999: 33.125 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 269640
  mean =      3.559 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3753 
    [ 2.500,  5.000) = 259306 
    [ 5.000,  7.500) = 5729 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     18.558 ms/op
     p(99.9900) =     31.130 ms/op
     p(99.9990) =     33.836 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.554 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.013 ms/op
Iteration   1: 3.503 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  11.541 ms/op
                 getUser·p0.9999: 25.297 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   2: 3.696 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  24.168 ms/op
                 getUser·p0.9999: 31.307 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 3.618 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.864 ms/op
                 getUser·p0.999:  25.663 ms/op
                 getUser·p0.9999: 34.548 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266272
  mean =      3.604 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5031 
    [ 2.500,  5.000) = 248477 
    [ 5.000,  7.500) = 10482 
    [ 7.500, 10.000) = 1673 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      3.469 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     34.103 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 14.518 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.498 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.015 ms/op
Iteration   1: 4.197 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.222 ms/op
                 listUser·p0.999:  23.953 ms/op
                 listUser·p0.9999: 25.958 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.175 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  16.127 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   20.349 ms/op

Iteration   3: 4.241 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.359 ms/op
                 listUser·p0.99:   8.130 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228160
  mean =      4.204 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 128 
    [ 2.500,  5.000) = 211260 
    [ 5.000,  7.500) = 13673 
    [ 7.500, 10.000) = 1872 
    [10.000, 12.500) = 552 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.886 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     18.574 ms/op
     p(99.9900) =     25.303 ms/op
     p(99.9990) =     26.472 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   8.357 ± 10.541  ops/ms
ClientPb.existUser                       thrpt       3   8.784 ±  5.520  ops/ms
ClientPb.getUser                         thrpt       3   8.547 ±  4.435  ops/ms
ClientPb.listUser                        thrpt       3   7.079 ±  8.936  ops/ms
ClientPb.createUser                       avgt       3   3.999 ±  0.413   ms/op
ClientPb.existUser                        avgt       3   3.632 ±  3.274   ms/op
ClientPb.getUser                          avgt       3   3.756 ±  1.504   ms/op
ClientPb.listUser                         avgt       3   4.459 ±  5.277   ms/op
ClientPb.createUser                     sample  263739   3.641 ±  0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.346            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.535            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.157            ms/op
ClientPb.createUser:createUser·p0.95    sample           4.497            ms/op
ClientPb.createUser:createUser·p0.99    sample           6.300            ms/op
ClientPb.createUser:createUser·p0.999   sample          15.450            ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.203            ms/op
ClientPb.createUser:createUser·p1.00    sample          32.768            ms/op
ClientPb.existUser                      sample  269640   3.559 ±  0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.803            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.494            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.006            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.415            ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005            ms/op
ClientPb.existUser:existUser·p0.999     sample          18.558            ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.130            ms/op
ClientPb.existUser:existUser·p1.00      sample          34.603            ms/op
ClientPb.getUser                        sample  266272   3.604 ±  0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.900            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.469            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.166            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.915            ms/op
ClientPb.getUser:getUser·p0.99          sample           7.242            ms/op
ClientPb.getUser:getUser·p0.999         sample          13.287            ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.103            ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783            ms/op
ClientPb.listUser                       sample  228160   4.204 ±  0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.886            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.809            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.317            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.339            ms/op
ClientPb.listUser:listUser·p0.999       sample          18.574            ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.303            ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066            ms/op
