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
# Warmup Iteration   1: 1.140 ops/ms
# Warmup Iteration   2: 2.545 ops/ms
# Warmup Iteration   3: 5.211 ops/ms
Iteration   1: 5.611 ops/ms
Iteration   2: 5.673 ops/ms
Iteration   3: 5.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.679 ±(99.9%) 1.301 ops/ms [Average]
  (min, avg, max) = (5.611, 5.679, 5.753), stdev = 0.071
  CI (99.9%): [4.378, 6.980] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.709 ops/ms
# Warmup Iteration   2: 4.904 ops/ms
# Warmup Iteration   3: 6.041 ops/ms
Iteration   1: 5.863 ops/ms
Iteration   2: 6.167 ops/ms
Iteration   3: 6.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.029 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (5.863, 6.029, 6.167), stdev = 0.154
  CI (99.9%): [3.215, 8.843] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.623 ops/ms
# Warmup Iteration   2: 4.426 ops/ms
# Warmup Iteration   3: 5.711 ops/ms
Iteration   1: 5.657 ops/ms
Iteration   2: 5.923 ops/ms
Iteration   3: 5.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.816 ±(99.9%) 2.556 ops/ms [Average]
  (min, avg, max) = (5.657, 5.816, 5.923), stdev = 0.140
  CI (99.9%): [3.260, 8.372] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.543 ops/ms
# Warmup Iteration   2: 4.175 ops/ms
# Warmup Iteration   3: 4.891 ops/ms
Iteration   1: 4.864 ops/ms
Iteration   2: 4.853 ops/ms
Iteration   3: 4.992 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.903 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (4.853, 4.903, 4.992), stdev = 0.077
  CI (99.9%): [3.498, 6.309] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 19.395 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.031 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.065 ±(99.9%) 0.016 ms/op
Iteration   1: 5.567 ±(99.9%) 0.007 ms/op
Iteration   2: 5.794 ±(99.9%) 0.007 ms/op
Iteration   3: 5.528 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.630 ±(99.9%) 2.619 ms/op [Average]
  (min, avg, max) = (5.528, 5.630, 5.794), stdev = 0.144
  CI (99.9%): [3.011, 8.249] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.543 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.086 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.324 ±(99.9%) 0.013 ms/op
Iteration   1: 5.408 ±(99.9%) 0.007 ms/op
Iteration   2: 5.148 ±(99.9%) 0.007 ms/op
Iteration   3: 5.224 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.260 ±(99.9%) 2.437 ms/op [Average]
  (min, avg, max) = (5.148, 5.260, 5.408), stdev = 0.134
  CI (99.9%): [2.824, 7.697] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 16.901 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.634 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.450 ±(99.9%) 0.013 ms/op
Iteration   1: 5.432 ±(99.9%) 0.015 ms/op
Iteration   2: 5.392 ±(99.9%) 0.008 ms/op
Iteration   3: 5.437 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.421 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (5.392, 5.421, 5.437), stdev = 0.025
  CI (99.9%): [4.973, 5.868] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.035 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 8.031 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.641 ±(99.9%) 0.009 ms/op
Iteration   1: 6.490 ±(99.9%) 0.015 ms/op
Iteration   2: 6.531 ±(99.9%) 0.012 ms/op
Iteration   3: 6.485 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.502 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (6.485, 6.502, 6.531), stdev = 0.025
  CI (99.9%): [6.045, 6.959] (assumes normal distribution)


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
# Warmup Iteration   1: 19.041 ±(99.9%) 0.324 ms/op
# Warmup Iteration   2: 6.835 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.022 ms/op
Iteration   1: 5.685 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   6.832 ms/op
                 createUser·p0.95:   7.865 ms/op
                 createUser·p0.99:   10.551 ms/op
                 createUser·p0.999:  23.513 ms/op
                 createUser·p0.9999: 28.553 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   2: 5.571 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.849 ms/op
                 createUser·p0.50:   5.284 ms/op
                 createUser·p0.90:   6.717 ms/op
                 createUser·p0.95:   7.463 ms/op
                 createUser·p0.99:   10.249 ms/op
                 createUser·p0.999:  27.656 ms/op
                 createUser·p0.9999: 34.082 ms/op
                 createUser·p1.00:   35.193 ms/op

Iteration   3: 5.479 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.617 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.184 ms/op
                 createUser·p0.99:   10.411 ms/op
                 createUser·p0.999:  27.754 ms/op
                 createUser·p0.9999: 30.938 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172037
  mean =      5.577 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 56560 
    [ 5.000,  7.500) = 107142 
    [ 7.500, 10.000) = 6241 
    [10.000, 12.500) = 1434 
    [12.500, 15.000) = 337 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.455 ms/op
     p(99.0000) =     10.387 ms/op
     p(99.9000) =     25.525 ms/op
     p(99.9900) =     33.253 ms/op
     p(99.9990) =     35.098 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 17.795 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.203 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.344 ±(99.9%) 0.018 ms/op
Iteration   1: 5.297 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.258 ms/op
                 existUser·p0.99:   9.863 ms/op
                 existUser·p0.999:  23.138 ms/op
                 existUser·p0.9999: 26.705 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   2: 5.392 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.314 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.554 ms/op
                 existUser·p0.95:   7.266 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  15.430 ms/op
                 existUser·p0.9999: 29.927 ms/op
                 existUser·p1.00:   30.900 ms/op

Iteration   3: 5.314 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.667 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.390 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   10.404 ms/op
                 existUser·p0.999:  26.575 ms/op
                 existUser·p0.9999: 32.408 ms/op
                 existUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179804
  mean =      5.334 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 85469 
    [ 5.000,  7.500) = 86543 
    [ 7.500, 10.000) = 6055 
    [10.000, 12.500) = 1188 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.463 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     20.355 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     33.156 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.015 ±(99.9%) 0.277 ms/op
# Warmup Iteration   2: 7.079 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 5.654 ±(99.9%) 0.021 ms/op
Iteration   1: 5.838 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.703 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   7.324 ms/op
                 getUser·p0.95:   9.126 ms/op
                 getUser·p0.99:   12.943 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 27.664 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   2: 5.804 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.009 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   7.037 ms/op
                 getUser·p0.95:   8.086 ms/op
                 getUser·p0.99:   11.600 ms/op
                 getUser·p0.999:  27.195 ms/op
                 getUser·p0.9999: 30.899 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 5.572 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.601 ms/op
                 getUser·p0.50:   5.300 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.348 ms/op
                 getUser·p0.99:   10.994 ms/op
                 getUser·p0.999:  27.860 ms/op
                 getUser·p0.9999: 31.254 ms/op
                 getUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167285
  mean =      5.735 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 40207 
    [ 5.000,  7.500) = 115285 
    [ 7.500, 10.000) = 7939 
    [10.000, 12.500) = 2515 
    [12.500, 15.000) = 835 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.009 ms/op
     p(50.0000) =      5.390 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      8.315 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     23.780 ms/op
     p(99.9900) =     30.855 ms/op
     p(99.9990) =     31.850 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 19.759 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 8.916 ±(99.9%) 0.079 ms/op
# Warmup Iteration   3: 6.764 ±(99.9%) 0.028 ms/op
Iteration   1: 6.656 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.851 ms/op
                 listUser·p0.50:   6.242 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.781 ms/op
                 listUser·p0.99:   13.932 ms/op
                 listUser·p0.999:  28.244 ms/op
                 listUser·p0.9999: 31.490 ms/op
                 listUser·p1.00:   32.506 ms/op

Iteration   2: 6.522 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.117 ms/op
                 listUser·p0.50:   6.250 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  30.600 ms/op
                 listUser·p0.9999: 43.850 ms/op
                 listUser·p1.00:   45.416 ms/op

Iteration   3: 6.402 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   12.203 ms/op
                 listUser·p0.999:  24.680 ms/op
                 listUser·p0.9999: 30.737 ms/op
                 listUser·p1.00:   31.195 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147062
  mean =      6.525 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3091 
    [ 5.000, 10.000) = 139414 
    [10.000, 15.000) = 3763 
    [15.000, 20.000) = 454 
    [20.000, 25.000) = 78 
    [25.000, 30.000) = 170 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.804 ms/op
     p(50.0000) =      6.210 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     12.812 ms/op
     p(99.9000) =     28.541 ms/op
     p(99.9900) =     43.207 ms/op
     p(99.9990) =     44.800 ms/op
     p(99.9999) =     45.416 ms/op
    p(100.0000) =     45.416 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.679 ± 1.301  ops/ms
ClientPb.existUser                       thrpt       3   6.029 ± 2.814  ops/ms
ClientPb.getUser                         thrpt       3   5.816 ± 2.556  ops/ms
ClientPb.listUser                        thrpt       3   4.903 ± 1.406  ops/ms
ClientPb.createUser                       avgt       3   5.630 ± 2.619   ms/op
ClientPb.existUser                        avgt       3   5.260 ± 2.437   ms/op
ClientPb.getUser                          avgt       3   5.421 ± 0.447   ms/op
ClientPb.listUser                         avgt       3   6.502 ± 0.457   ms/op
ClientPb.createUser                     sample  172037   5.577 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.491           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.387           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.525           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.253           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.193           ms/op
ClientPb.existUser                      sample  179804   5.334 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.867           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.880           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.355           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.474           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.522           ms/op
ClientPb.getUser                        sample  167285   5.735 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.009           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.390           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.315           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.862           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.780           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.855           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.916           ms/op
ClientPb.listUser                       sample  147062   6.525 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.804           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.880           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.812           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.541           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.207           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.416           ms/op
