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
# Warmup Iteration   1: 1.090 ops/ms
# Warmup Iteration   2: 2.169 ops/ms
# Warmup Iteration   3: 4.695 ops/ms
Iteration   1: 5.302 ops/ms
Iteration   2: 5.521 ops/ms
Iteration   3: 5.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.525 ±(99.9%) 4.108 ops/ms [Average]
  (min, avg, max) = (5.302, 5.525, 5.753), stdev = 0.225
  CI (99.9%): [1.418, 9.633] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.599 ops/ms
# Warmup Iteration   2: 4.101 ops/ms
# Warmup Iteration   3: 5.590 ops/ms
Iteration   1: 6.007 ops/ms
Iteration   2: 5.763 ops/ms
Iteration   3: 5.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.888 ±(99.9%) 2.230 ops/ms [Average]
  (min, avg, max) = (5.763, 5.888, 6.007), stdev = 0.122
  CI (99.9%): [3.658, 8.117] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.361 ops/ms
# Warmup Iteration   2: 3.914 ops/ms
# Warmup Iteration   3: 5.529 ops/ms
Iteration   1: 5.510 ops/ms
Iteration   2: 5.642 ops/ms
Iteration   3: 5.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.563 ±(99.9%) 1.268 ops/ms [Average]
  (min, avg, max) = (5.510, 5.563, 5.642), stdev = 0.070
  CI (99.9%): [4.295, 6.831] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.448 ops/ms
# Warmup Iteration   2: 3.234 ops/ms
# Warmup Iteration   3: 4.570 ops/ms
Iteration   1: 4.633 ops/ms
Iteration   2: 4.885 ops/ms
Iteration   3: 4.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.783 ±(99.9%) 2.419 ops/ms [Average]
  (min, avg, max) = (4.633, 4.783, 4.885), stdev = 0.133
  CI (99.9%): [2.364, 7.202] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 20.304 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 7.638 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.906 ±(99.9%) 0.014 ms/op
Iteration   1: 5.918 ±(99.9%) 0.014 ms/op
Iteration   2: 5.730 ±(99.9%) 0.012 ms/op
Iteration   3: 5.754 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.801 ±(99.9%) 1.863 ms/op [Average]
  (min, avg, max) = (5.730, 5.801, 5.918), stdev = 0.102
  CI (99.9%): [3.937, 7.664] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.815 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 6.163 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.619 ±(99.9%) 0.016 ms/op
Iteration   1: 5.349 ±(99.9%) 0.015 ms/op
Iteration   2: 5.550 ±(99.9%) 0.013 ms/op
Iteration   3: 5.559 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.486 ±(99.9%) 2.171 ms/op [Average]
  (min, avg, max) = (5.349, 5.486, 5.559), stdev = 0.119
  CI (99.9%): [3.315, 7.657] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.869 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.844 ±(99.9%) 0.011 ms/op
Iteration   1: 5.585 ±(99.9%) 0.017 ms/op
Iteration   2: 5.750 ±(99.9%) 0.010 ms/op
Iteration   3: 5.465 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.600 ±(99.9%) 2.611 ms/op [Average]
  (min, avg, max) = (5.465, 5.600, 5.750), stdev = 0.143
  CI (99.9%): [2.989, 8.211] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.387 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 8.619 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 6.686 ±(99.9%) 0.012 ms/op
Iteration   1: 6.674 ±(99.9%) 0.013 ms/op
Iteration   2: 6.435 ±(99.9%) 0.020 ms/op
Iteration   3: 6.486 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.532 ±(99.9%) 2.297 ms/op [Average]
  (min, avg, max) = (6.435, 6.532, 6.674), stdev = 0.126
  CI (99.9%): [4.235, 8.829] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 21.283 ±(99.9%) 0.399 ms/op
# Warmup Iteration   2: 8.073 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.424 ±(99.9%) 0.030 ms/op
Iteration   1: 5.643 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.474 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   7.039 ms/op
                 createUser·p0.95:   8.020 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  20.087 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   2: 5.711 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.425 ms/op
                 createUser·p0.50:   5.366 ms/op
                 createUser·p0.90:   7.070 ms/op
                 createUser·p0.95:   8.045 ms/op
                 createUser·p0.99:   10.603 ms/op
                 createUser·p0.999:  32.606 ms/op
                 createUser·p0.9999: 43.123 ms/op
                 createUser·p1.00:   43.516 ms/op

Iteration   3: 5.813 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.234 ms/op
                 createUser·p0.95:   8.217 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  30.474 ms/op
                 createUser·p0.9999: 35.848 ms/op
                 createUser·p1.00:   36.766 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167718
  mean =      5.722 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 51190 
    [ 5.000, 10.000) = 113968 
    [10.000, 15.000) = 2096 
    [15.000, 20.000) = 224 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 33 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.110 ms/op
     p(99.0000) =     10.781 ms/op
     p(99.9000) =     28.279 ms/op
     p(99.9900) =     40.713 ms/op
     p(99.9990) =     43.383 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.079 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.339 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.817 ±(99.9%) 0.024 ms/op
Iteration   1: 5.425 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   8.118 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  24.576 ms/op
                 existUser·p0.9999: 27.730 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   2: 5.592 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.384 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.947 ms/op
                 existUser·p0.95:   7.782 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  26.094 ms/op
                 existUser·p0.9999: 30.558 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   3: 5.385 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.619 ms/op
                 existUser·p0.95:   7.496 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  26.957 ms/op
                 existUser·p0.9999: 32.510 ms/op
                 existUser·p1.00:   37.814 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175449
  mean =      5.466 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 67983 
    [ 5.000,  7.500) = 96800 
    [ 7.500, 10.000) = 8235 
    [10.000, 12.500) = 1700 
    [12.500, 15.000) = 468 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     24.954 ms/op
     p(99.9900) =     31.996 ms/op
     p(99.9990) =     34.402 ms/op
     p(99.9999) =     37.814 ms/op
    p(100.0000) =     37.814 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.672 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 7.023 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.684 ±(99.9%) 0.022 ms/op
Iteration   1: 5.862 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   5.366 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   9.175 ms/op
                 getUser·p0.99:   13.785 ms/op
                 getUser·p0.999:  23.968 ms/op
                 getUser·p0.9999: 28.002 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   2: 5.659 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.765 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   6.857 ms/op
                 getUser·p0.95:   7.791 ms/op
                 getUser·p0.99:   10.838 ms/op
                 getUser·p0.999:  28.098 ms/op
                 getUser·p0.9999: 31.973 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   3: 5.603 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.839 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   6.889 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   10.617 ms/op
                 getUser·p0.999:  26.114 ms/op
                 getUser·p0.9999: 29.792 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168109
  mean =      5.706 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 50169 
    [ 5.000,  7.500) = 104930 
    [ 7.500, 10.000) = 9572 
    [10.000, 12.500) = 2054 
    [12.500, 15.000) = 713 
    [15.000, 17.500) = 343 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.380 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.070 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     31.240 ms/op
     p(99.9990) =     32.610 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.907 ±(99.9%) 0.389 ms/op
# Warmup Iteration   2: 8.713 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 7.089 ±(99.9%) 0.030 ms/op
Iteration   1: 6.450 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.763 ms/op
                 listUser·p0.999:  30.259 ms/op
                 listUser·p0.9999: 33.620 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   2: 6.559 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.580 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.406 ms/op
                 listUser·p0.999:  31.800 ms/op
                 listUser·p0.9999: 38.502 ms/op
                 listUser·p1.00:   39.453 ms/op

Iteration   3: 6.820 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.520 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   12.943 ms/op
                 listUser·p0.999:  26.990 ms/op
                 listUser·p0.9999: 35.668 ms/op
                 listUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145231
  mean =      6.606 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 4130 
    [ 5.000,  7.500) = 118255 
    [ 7.500, 10.000) = 17182 
    [10.000, 12.500) = 4055 
    [12.500, 15.000) = 1003 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 60 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      8.225 ms/op
     p(95.0000) =      9.601 ms/op
     p(99.0000) =     12.763 ms/op
     p(99.9000) =     30.245 ms/op
     p(99.9900) =     37.456 ms/op
     p(99.9990) =     39.127 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.525 ± 4.108  ops/ms
ClientPb.existUser                       thrpt       3   5.888 ± 2.230  ops/ms
ClientPb.getUser                         thrpt       3   5.563 ± 1.268  ops/ms
ClientPb.listUser                        thrpt       3   4.783 ± 2.419  ops/ms
ClientPb.createUser                       avgt       3   5.801 ± 1.863   ms/op
ClientPb.existUser                        avgt       3   5.486 ± 2.171   ms/op
ClientPb.getUser                          avgt       3   5.600 ± 2.611   ms/op
ClientPb.listUser                         avgt       3   6.532 ± 2.297   ms/op
ClientPb.createUser                     sample  167718   5.722 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.179           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.110           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.781           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.279           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.713           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.516           ms/op
ClientPb.existUser                      sample  175449   5.466 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.636           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.824           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.807           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.519           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.954           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.996           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.814           ms/op
ClientPb.getUser                        sample  168109   5.706 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.380           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.349           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.070           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.642           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.240           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  145231   6.606 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.580           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.225           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.601           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.763           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.245           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.456           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.453           ms/op
