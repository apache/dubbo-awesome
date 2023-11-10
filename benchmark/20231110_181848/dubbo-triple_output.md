# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.226 ops/ms
# Warmup Iteration   2: 2.822 ops/ms
# Warmup Iteration   3: 5.804 ops/ms
Iteration   1: 5.708 ops/ms
Iteration   2: 5.504 ops/ms
Iteration   3: 5.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.691 ±(99.9%) 3.264 ops/ms [Average]
  (min, avg, max) = (5.504, 5.691, 5.860), stdev = 0.179
  CI (99.9%): [2.427, 8.955] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.644 ops/ms
# Warmup Iteration   2: 4.835 ops/ms
# Warmup Iteration   3: 5.906 ops/ms
Iteration   1: 5.856 ops/ms
Iteration   2: 5.860 ops/ms
Iteration   3: 6.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.951 ±(99.9%) 2.947 ops/ms [Average]
  (min, avg, max) = (5.856, 5.951, 6.138), stdev = 0.162
  CI (99.9%): [3.004, 8.898] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.357 ops/ms
# Warmup Iteration   2: 4.030 ops/ms
# Warmup Iteration   3: 5.617 ops/ms
Iteration   1: 5.734 ops/ms
Iteration   2: 5.830 ops/ms
Iteration   3: 5.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.824 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (5.734, 5.824, 5.908), stdev = 0.088
  CI (99.9%): [4.227, 7.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.454 ops/ms
# Warmup Iteration   2: 3.765 ops/ms
# Warmup Iteration   3: 4.748 ops/ms
Iteration   1: 4.948 ops/ms
Iteration   2: 4.977 ops/ms
Iteration   3: 5.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.009 ±(99.9%) 1.481 ops/ms [Average]
  (min, avg, max) = (4.948, 5.009, 5.101), stdev = 0.081
  CI (99.9%): [3.528, 6.489] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.172 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.319 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.651 ±(99.9%) 0.011 ms/op
Iteration   1: 5.606 ±(99.9%) 0.010 ms/op
Iteration   2: 5.462 ±(99.9%) 0.012 ms/op
Iteration   3: 5.521 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.530 ±(99.9%) 1.320 ms/op [Average]
  (min, avg, max) = (5.462, 5.530, 5.606), stdev = 0.072
  CI (99.9%): [4.209, 6.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 18.084 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 7.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.355 ±(99.9%) 0.011 ms/op
Iteration   1: 5.548 ±(99.9%) 0.012 ms/op
Iteration   2: 5.214 ±(99.9%) 0.012 ms/op
Iteration   3: 5.213 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.325 ±(99.9%) 3.518 ms/op [Average]
  (min, avg, max) = (5.213, 5.325, 5.548), stdev = 0.193
  CI (99.9%): [1.807, 8.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.248 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.899 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.868 ±(99.9%) 0.009 ms/op
Iteration   1: 5.862 ±(99.9%) 0.009 ms/op
Iteration   2: 5.618 ±(99.9%) 0.007 ms/op
Iteration   3: 5.522 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.667 ±(99.9%) 3.189 ms/op [Average]
  (min, avg, max) = (5.522, 5.667, 5.862), stdev = 0.175
  CI (99.9%): [2.478, 8.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.797 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 8.237 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.718 ±(99.9%) 0.011 ms/op
Iteration   1: 6.716 ±(99.9%) 0.010 ms/op
Iteration   2: 6.568 ±(99.9%) 0.022 ms/op
Iteration   3: 6.563 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.616 ±(99.9%) 1.589 ms/op [Average]
  (min, avg, max) = (6.563, 6.616, 6.716), stdev = 0.087
  CI (99.9%): [5.026, 8.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.680 ±(99.9%) 0.334 ms/op
# Warmup Iteration   2: 7.103 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.050 ±(99.9%) 0.028 ms/op
Iteration   1: 5.583 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.388 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.078 ms/op
                 createUser·p0.95:   8.365 ms/op
                 createUser·p0.99:   11.452 ms/op
                 createUser·p0.999:  15.544 ms/op
                 createUser·p0.9999: 26.485 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 5.617 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.519 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   8.127 ms/op
                 createUser·p0.99:   11.607 ms/op
                 createUser·p0.999:  26.104 ms/op
                 createUser·p0.9999: 35.213 ms/op
                 createUser·p1.00:   35.652 ms/op

Iteration   3: 5.654 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.894 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.963 ms/op
                 createUser·p0.95:   7.954 ms/op
                 createUser·p0.99:   11.043 ms/op
                 createUser·p0.999:  28.358 ms/op
                 createUser·p0.9999: 31.785 ms/op
                 createUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170791
  mean =      5.618 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 59974 
    [ 5.000,  7.500) = 98047 
    [ 7.500, 10.000) = 9566 
    [10.000, 12.500) = 2080 
    [12.500, 15.000) = 697 
    [15.000, 17.500) = 225 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.894 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.029 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     19.012 ms/op
     p(99.9900) =     33.254 ms/op
     p(99.9990) =     35.559 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.032 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 6.856 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.541 ±(99.9%) 0.022 ms/op
Iteration   1: 5.476 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.224 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.323 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  17.820 ms/op
                 existUser·p0.9999: 26.546 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 5.480 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   7.005 ms/op
                 existUser·p0.95:   8.282 ms/op
                 existUser·p0.99:   11.703 ms/op
                 existUser·p0.999:  25.359 ms/op
                 existUser·p0.9999: 29.808 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 5.589 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.306 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   7.299 ms/op
                 existUser·p0.95:   8.782 ms/op
                 existUser·p0.99:   12.403 ms/op
                 existUser·p0.999:  30.886 ms/op
                 existUser·p0.9999: 33.769 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173967
  mean =      5.515 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 75929 
    [ 5.000,  7.500) = 83896 
    [ 7.500, 10.000) = 10023 
    [10.000, 12.500) = 2805 
    [12.500, 15.000) = 753 
    [15.000, 17.500) = 285 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      7.086 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.764 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     32.821 ms/op
     p(99.9990) =     34.167 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.420 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.441 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.659 ±(99.9%) 0.024 ms/op
Iteration   1: 5.744 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   7.512 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   13.910 ms/op
                 getUser·p0.999:  25.165 ms/op
                 getUser·p0.9999: 34.435 ms/op
                 getUser·p1.00:   34.800 ms/op

Iteration   2: 5.476 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   5.136 ms/op
                 getUser·p0.90:   6.829 ms/op
                 getUser·p0.95:   8.118 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  27.545 ms/op
                 getUser·p0.9999: 32.924 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   3: 5.437 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   6.734 ms/op
                 getUser·p0.95:   7.676 ms/op
                 getUser·p0.99:   11.026 ms/op
                 getUser·p0.999:  18.125 ms/op
                 getUser·p0.9999: 32.288 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172924
  mean =      5.549 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 70738 
    [ 5.000,  7.500) = 89112 
    [ 7.500, 10.000) = 9398 
    [10.000, 12.500) = 2154 
    [12.500, 15.000) = 875 
    [15.000, 17.500) = 267 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 37 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.988 ms/op
     p(95.0000) =      8.217 ms/op
     p(99.0000) =     12.059 ms/op
     p(99.9000) =     23.366 ms/op
     p(99.9900) =     33.797 ms/op
     p(99.9990) =     34.656 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.712 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.422 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.512 ±(99.9%) 0.027 ms/op
Iteration   1: 6.306 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.445 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.709 ms/op
                 listUser·p0.95:   9.077 ms/op
                 listUser·p0.99:   12.583 ms/op
                 listUser·p0.999:  27.731 ms/op
                 listUser·p0.9999: 32.096 ms/op
                 listUser·p1.00:   32.440 ms/op

Iteration   2: 6.307 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   7.660 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  30.876 ms/op
                 listUser·p0.9999: 34.991 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   3: 6.230 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   5.906 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  23.726 ms/op
                 listUser·p0.9999: 29.323 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152777
  mean =      6.281 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 9531 
    [ 5.000,  7.500) = 126571 
    [ 7.500, 10.000) = 12452 
    [10.000, 12.500) = 2797 
    [12.500, 15.000) = 869 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.627 ms/op
     p(95.0000) =      8.864 ms/op
     p(99.0000) =     12.374 ms/op
     p(99.9000) =     27.329 ms/op
     p(99.9900) =     32.946 ms/op
     p(99.9990) =     36.496 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.691 ± 3.264  ops/ms
ClientPb.existUser                       thrpt       3   5.951 ± 2.947  ops/ms
ClientPb.getUser                         thrpt       3   5.824 ± 1.597  ops/ms
ClientPb.listUser                        thrpt       3   5.009 ± 1.481  ops/ms
ClientPb.createUser                       avgt       3   5.530 ± 1.320   ms/op
ClientPb.existUser                        avgt       3   5.325 ± 3.518   ms/op
ClientPb.getUser                          avgt       3   5.667 ± 3.189   ms/op
ClientPb.listUser                         avgt       3   6.616 ± 1.589   ms/op
ClientPb.createUser                     sample  170791   5.618 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.894           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.143           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.420           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.012           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.652           ms/op
ClientPb.existUser                      sample  173967   5.515 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.753           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.503           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.764           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.251           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.821           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.603           ms/op
ClientPb.getUser                        sample  172924   5.549 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.988           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.217           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.059           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.797           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.800           ms/op
ClientPb.listUser                       sample  152777   6.281 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.864           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.374           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.329           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.946           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.635           ms/op
