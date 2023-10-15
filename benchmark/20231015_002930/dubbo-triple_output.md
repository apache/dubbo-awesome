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
# Warmup Iteration   1: 1.155 ops/ms
# Warmup Iteration   2: 2.570 ops/ms
# Warmup Iteration   3: 5.133 ops/ms
Iteration   1: 5.590 ops/ms
Iteration   2: 5.788 ops/ms
Iteration   3: 5.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.771 ±(99.9%) 3.171 ops/ms [Average]
  (min, avg, max) = (5.590, 5.771, 5.936), stdev = 0.174
  CI (99.9%): [2.600, 8.942] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.657 ops/ms
# Warmup Iteration   2: 5.008 ops/ms
# Warmup Iteration   3: 6.056 ops/ms
Iteration   1: 5.947 ops/ms
Iteration   2: 5.892 ops/ms
Iteration   3: 6.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.971 ±(99.9%) 1.716 ops/ms [Average]
  (min, avg, max) = (5.892, 5.971, 6.075), stdev = 0.094
  CI (99.9%): [4.256, 7.687] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.794 ops/ms
# Warmup Iteration   2: 4.520 ops/ms
# Warmup Iteration   3: 5.995 ops/ms
Iteration   1: 5.581 ops/ms
Iteration   2: 5.776 ops/ms
Iteration   3: 5.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.704 ±(99.9%) 1.956 ops/ms [Average]
  (min, avg, max) = (5.581, 5.704, 5.776), stdev = 0.107
  CI (99.9%): [3.748, 7.661] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.728 ops/ms
# Warmup Iteration   2: 3.850 ops/ms
# Warmup Iteration   3: 4.778 ops/ms
Iteration   1: 4.718 ops/ms
Iteration   2: 4.881 ops/ms
Iteration   3: 4.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.864 ±(99.9%) 2.534 ops/ms [Average]
  (min, avg, max) = (4.718, 4.864, 4.994), stdev = 0.139
  CI (99.9%): [2.330, 7.398] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.913 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 7.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.769 ±(99.9%) 0.006 ms/op
Iteration   1: 5.786 ±(99.9%) 0.010 ms/op
Iteration   2: 5.430 ±(99.9%) 0.009 ms/op
Iteration   3: 5.648 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.621 ±(99.9%) 3.276 ms/op [Average]
  (min, avg, max) = (5.430, 5.621, 5.786), stdev = 0.180
  CI (99.9%): [2.346, 8.897] (assumes normal distribution)


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
# Warmup Iteration   1: 17.009 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.254 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.010 ms/op
Iteration   1: 5.429 ±(99.9%) 0.012 ms/op
Iteration   2: 5.206 ±(99.9%) 0.010 ms/op
Iteration   3: 5.331 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.322 ±(99.9%) 2.035 ms/op [Average]
  (min, avg, max) = (5.206, 5.322, 5.429), stdev = 0.112
  CI (99.9%): [3.287, 7.357] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 15.108 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.584 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.746 ±(99.9%) 0.011 ms/op
Iteration   1: 5.446 ±(99.9%) 0.012 ms/op
Iteration   2: 5.510 ±(99.9%) 0.011 ms/op
Iteration   3: 5.610 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.522 ±(99.9%) 1.507 ms/op [Average]
  (min, avg, max) = (5.446, 5.522, 5.610), stdev = 0.083
  CI (99.9%): [4.015, 7.029] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.727 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 7.331 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.722 ±(99.9%) 0.013 ms/op
Iteration   1: 6.387 ±(99.9%) 0.014 ms/op
Iteration   2: 6.219 ±(99.9%) 0.016 ms/op
Iteration   3: 6.558 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.388 ±(99.9%) 3.092 ms/op [Average]
  (min, avg, max) = (6.219, 6.388, 6.558), stdev = 0.169
  CI (99.9%): [3.296, 9.480] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 15.910 ±(99.9%) 0.285 ms/op
# Warmup Iteration   2: 6.507 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.437 ±(99.9%) 0.032 ms/op
Iteration   1: 5.476 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.503 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.815 ms/op
                 createUser·p0.99:   10.027 ms/op
                 createUser·p0.999:  25.709 ms/op
                 createUser·p0.9999: 33.494 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   2: 5.620 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   6.767 ms/op
                 createUser·p0.95:   7.455 ms/op
                 createUser·p0.99:   9.773 ms/op
                 createUser·p0.999:  25.928 ms/op
                 createUser·p0.9999: 31.818 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 5.798 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.568 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.356 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   11.599 ms/op
                 createUser·p0.999:  28.738 ms/op
                 createUser·p0.9999: 32.470 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170555
  mean =      5.628 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 56199 
    [ 5.000,  7.500) = 102908 
    [ 7.500, 10.000) = 9464 
    [10.000, 12.500) = 1133 
    [12.500, 15.000) = 474 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.913 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.021 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     10.486 ms/op
     p(99.9000) =     26.229 ms/op
     p(99.9900) =     32.535 ms/op
     p(99.9990) =     34.179 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.025 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 6.174 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.576 ±(99.9%) 0.021 ms/op
Iteration   1: 5.350 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   5.063 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.668 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  21.251 ms/op
                 existUser·p0.9999: 24.676 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   2: 5.271 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   5.030 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   9.896 ms/op
                 existUser·p0.999:  23.364 ms/op
                 existUser·p0.9999: 27.787 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   3: 5.561 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   5.251 ms/op
                 existUser·p0.90:   7.070 ms/op
                 existUser·p0.95:   8.110 ms/op
                 existUser·p0.99:   11.878 ms/op
                 existUser·p0.999:  16.482 ms/op
                 existUser·p0.9999: 27.500 ms/op
                 existUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177984
  mean =      5.391 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 81201 
    [ 5.000,  7.500) = 86517 
    [ 7.500, 10.000) = 7626 
    [10.000, 12.500) = 1816 
    [12.500, 15.000) = 490 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.750 ms/op
     p(95.0000) =      7.700 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     18.024 ms/op
     p(99.9900) =     27.433 ms/op
     p(99.9990) =     28.497 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 16.633 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.145 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.553 ±(99.9%) 0.019 ms/op
Iteration   1: 5.520 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.654 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   7.610 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  24.412 ms/op
                 getUser·p0.9999: 27.090 ms/op
                 getUser·p1.00:   28.443 ms/op

Iteration   2: 5.540 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.728 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.569 ms/op
                 getUser·p0.99:   11.895 ms/op
                 getUser·p0.999:  24.889 ms/op
                 getUser·p0.9999: 28.163 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 5.460 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.507 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.340 ms/op
                 getUser·p0.99:   9.273 ms/op
                 getUser·p0.999:  14.718 ms/op
                 getUser·p0.9999: 29.594 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174309
  mean =      5.507 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 72394 
    [ 5.000,  7.500) = 90992 
    [ 7.500, 10.000) = 8520 
    [10.000, 12.500) = 1556 
    [12.500, 15.000) = 360 
    [15.000, 17.500) = 190 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.507 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.823 ms/op
     p(99.0000) =     10.715 ms/op
     p(99.9000) =     22.807 ms/op
     p(99.9900) =     28.429 ms/op
     p(99.9990) =     30.453 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 19.380 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 7.226 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.654 ±(99.9%) 0.024 ms/op
Iteration   1: 6.827 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.662 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.421 ms/op
                 listUser·p0.99:   12.763 ms/op
                 listUser·p0.999:  26.444 ms/op
                 listUser·p0.9999: 29.653 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 6.636 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   8.258 ms/op
                 listUser·p0.95:   9.224 ms/op
                 listUser·p0.99:   12.486 ms/op
                 listUser·p0.999:  28.180 ms/op
                 listUser·p0.9999: 31.600 ms/op
                 listUser·p1.00:   33.161 ms/op

Iteration   3: 6.383 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.269 ms/op
                 listUser·p0.50:   6.038 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   12.091 ms/op
                 listUser·p0.999:  23.721 ms/op
                 listUser·p0.9999: 28.934 ms/op
                 listUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145166
  mean =      6.610 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 6055 
    [ 5.000,  7.500) = 113353 
    [ 7.500, 10.000) = 21421 
    [10.000, 12.500) = 2834 
    [12.500, 15.000) = 860 
    [15.000, 17.500) = 283 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 84 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.923 ms/op
     p(50.0000) =      6.242 ms/op
     p(90.0000) =      8.184 ms/op
     p(95.0000) =      9.175 ms/op
     p(99.0000) =     12.550 ms/op
     p(99.9000) =     26.400 ms/op
     p(99.9900) =     30.275 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.771 ± 3.171  ops/ms
ClientPb.existUser                       thrpt       3   5.971 ± 1.716  ops/ms
ClientPb.getUser                         thrpt       3   5.704 ± 1.956  ops/ms
ClientPb.listUser                        thrpt       3   4.864 ± 2.534  ops/ms
ClientPb.createUser                       avgt       3   5.621 ± 3.276   ms/op
ClientPb.existUser                        avgt       3   5.322 ± 2.035   ms/op
ClientPb.getUser                          avgt       3   5.522 ± 1.507   ms/op
ClientPb.listUser                         avgt       3   6.388 ± 3.092   ms/op
ClientPb.createUser                     sample  170555   5.628 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.423           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.021           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.486           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.229           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.535           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  177984   5.391 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.748           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.024           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.433           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  174309   5.507 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.873           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.823           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.715           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.429           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  145166   6.610 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.242           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.184           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.175           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.550           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.400           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.275           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.161           ms/op
