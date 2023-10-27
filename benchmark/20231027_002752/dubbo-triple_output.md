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
# Warmup Iteration   1: 0.854 ops/ms
# Warmup Iteration   2: 2.064 ops/ms
# Warmup Iteration   3: 4.522 ops/ms
Iteration   1: 4.950 ops/ms
Iteration   2: 4.989 ops/ms
Iteration   3: 5.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.015 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (4.950, 5.015, 5.108), stdev = 0.082
  CI (99.9%): [3.513, 6.517] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.335 ops/ms
# Warmup Iteration   2: 3.824 ops/ms
# Warmup Iteration   3: 5.023 ops/ms
Iteration   1: 5.380 ops/ms
Iteration   2: 5.518 ops/ms
Iteration   3: 5.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.487 ±(99.9%) 1.738 ops/ms [Average]
  (min, avg, max) = (5.380, 5.487, 5.563), stdev = 0.095
  CI (99.9%): [3.749, 7.225] (assumes normal distribution)


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
# Warmup Iteration   1: 1.170 ops/ms
# Warmup Iteration   2: 3.612 ops/ms
# Warmup Iteration   3: 4.985 ops/ms
Iteration   1: 5.112 ops/ms
Iteration   2: 5.110 ops/ms
Iteration   3: 5.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.159 ±(99.9%) 1.528 ops/ms [Average]
  (min, avg, max) = (5.110, 5.159, 5.256), stdev = 0.084
  CI (99.9%): [3.632, 6.687] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.448 ops/ms
# Warmup Iteration   2: 3.731 ops/ms
# Warmup Iteration   3: 4.307 ops/ms
Iteration   1: 4.344 ops/ms
Iteration   2: 4.397 ops/ms
Iteration   3: 4.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.359 ±(99.9%) 0.591 ops/ms [Average]
  (min, avg, max) = (4.337, 4.359, 4.397), stdev = 0.032
  CI (99.9%): [3.768, 4.951] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 25.494 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 9.510 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.256 ±(99.9%) 0.006 ms/op
Iteration   1: 6.274 ±(99.9%) 0.007 ms/op
Iteration   2: 5.974 ±(99.9%) 0.015 ms/op
Iteration   3: 6.096 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.115 ±(99.9%) 2.749 ms/op [Average]
  (min, avg, max) = (5.974, 6.115, 6.274), stdev = 0.151
  CI (99.9%): [3.365, 8.864] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 23.510 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 7.331 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.047 ±(99.9%) 0.011 ms/op
Iteration   1: 6.041 ±(99.9%) 0.007 ms/op
Iteration   2: 5.736 ±(99.9%) 0.009 ms/op
Iteration   3: 5.725 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.834 ±(99.9%) 3.276 ms/op [Average]
  (min, avg, max) = (5.725, 5.834, 6.041), stdev = 0.180
  CI (99.9%): [2.558, 9.109] (assumes normal distribution)


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
# Warmup Iteration   1: 22.188 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 8.417 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.358 ±(99.9%) 0.009 ms/op
Iteration   1: 6.531 ±(99.9%) 0.010 ms/op
Iteration   2: 6.062 ±(99.9%) 0.011 ms/op
Iteration   3: 6.301 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.298 ±(99.9%) 4.277 ms/op [Average]
  (min, avg, max) = (6.062, 6.298, 6.531), stdev = 0.234
  CI (99.9%): [2.020, 10.575] (assumes normal distribution)


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
# Warmup Iteration   1: 22.840 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 8.796 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 7.359 ±(99.9%) 0.015 ms/op
Iteration   1: 7.359 ±(99.9%) 0.017 ms/op
Iteration   2: 7.059 ±(99.9%) 0.019 ms/op
Iteration   3: 7.329 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.249 ±(99.9%) 3.009 ms/op [Average]
  (min, avg, max) = (7.059, 7.249, 7.359), stdev = 0.165
  CI (99.9%): [4.240, 10.258] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.169 ±(99.9%) 0.343 ms/op
# Warmup Iteration   2: 8.171 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.417 ±(99.9%) 0.031 ms/op
Iteration   1: 5.963 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.163 ms/op
                 createUser·p0.50:   5.554 ms/op
                 createUser·p0.90:   7.725 ms/op
                 createUser·p0.95:   8.880 ms/op
                 createUser·p0.99:   11.633 ms/op
                 createUser·p0.999:  20.669 ms/op
                 createUser·p0.9999: 28.964 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   2: 5.944 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.800 ms/op
                 createUser·p0.50:   5.497 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   9.077 ms/op
                 createUser·p0.99:   13.025 ms/op
                 createUser·p0.999:  29.065 ms/op
                 createUser·p0.9999: 31.687 ms/op
                 createUser·p1.00:   32.244 ms/op

Iteration   3: 6.329 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   2.654 ms/op
                 createUser·p0.50:   5.890 ms/op
                 createUser·p0.90:   8.086 ms/op
                 createUser·p0.95:   9.322 ms/op
                 createUser·p0.99:   12.780 ms/op
                 createUser·p0.999:  32.456 ms/op
                 createUser·p0.9999: 43.316 ms/op
                 createUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 157955
  mean =      6.074 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 32793 
    [ 5.000, 10.000) = 120193 
    [10.000, 15.000) = 4255 
    [15.000, 20.000) = 479 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 83 
    [30.000, 35.000) = 61 
    [35.000, 40.000) = 19 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      5.636 ms/op
     p(90.0000) =      7.823 ms/op
     p(95.0000) =      9.093 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     27.692 ms/op
     p(99.9900) =     37.653 ms/op
     p(99.9990) =     43.637 ms/op
     p(99.9999) =     43.713 ms/op
    p(100.0000) =     43.713 ms/op


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
# Warmup Iteration   1: 20.161 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 7.132 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.893 ±(99.9%) 0.024 ms/op
Iteration   1: 5.893 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.413 ms/op
                 existUser·p0.50:   5.317 ms/op
                 existUser·p0.90:   7.946 ms/op
                 existUser·p0.95:   9.126 ms/op
                 existUser·p0.99:   12.829 ms/op
                 existUser·p0.999:  19.139 ms/op
                 existUser·p0.9999: 28.011 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   2: 5.723 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.408 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.208 ms/op
                 existUser·p0.99:   11.008 ms/op
                 existUser·p0.999:  24.153 ms/op
                 existUser·p0.9999: 28.882 ms/op
                 existUser·p1.00:   29.590 ms/op

Iteration   3: 5.714 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   7.455 ms/op
                 existUser·p0.95:   8.618 ms/op
                 existUser·p0.99:   11.403 ms/op
                 existUser·p0.999:  18.581 ms/op
                 existUser·p0.9999: 31.222 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 166178
  mean =      5.776 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 57561 
    [ 5.000,  7.500) = 91641 
    [ 7.500, 10.000) = 13294 
    [10.000, 12.500) = 2481 
    [12.500, 15.000) = 652 
    [15.000, 17.500) = 278 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.528 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     29.095 ms/op
     p(99.9990) =     31.829 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 19.959 ±(99.9%) 0.348 ms/op
# Warmup Iteration   2: 7.149 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.169 ±(99.9%) 0.028 ms/op
Iteration   1: 5.923 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.650 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.586 ms/op
                 getUser·p0.95:   9.044 ms/op
                 getUser·p0.99:   11.944 ms/op
                 getUser·p0.999:  19.268 ms/op
                 getUser·p0.9999: 27.401 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 5.964 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.593 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.660 ms/op
                 getUser·p0.95:   8.831 ms/op
                 getUser·p0.99:   11.485 ms/op
                 getUser·p0.999:  28.272 ms/op
                 getUser·p0.9999: 35.712 ms/op
                 getUser·p1.00:   35.848 ms/op

Iteration   3: 5.839 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.299 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   11.223 ms/op
                 getUser·p0.999:  25.110 ms/op
                 getUser·p0.9999: 28.641 ms/op
                 getUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162299
  mean =      5.908 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 38300 
    [ 5.000,  7.500) = 107725 
    [ 7.500, 10.000) = 12315 
    [10.000, 12.500) = 2921 
    [12.500, 15.000) = 557 
    [15.000, 17.500) = 224 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      2.593 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.504 ms/op
     p(95.0000) =      8.749 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     23.881 ms/op
     p(99.9900) =     34.689 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 21.641 ±(99.9%) 0.356 ms/op
# Warmup Iteration   2: 8.300 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 7.132 ±(99.9%) 0.034 ms/op
Iteration   1: 7.199 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   3.514 ms/op
                 listUser·p0.50:   6.652 ms/op
                 listUser·p0.90:   9.306 ms/op
                 listUser·p0.95:   11.108 ms/op
                 listUser·p0.99:   14.811 ms/op
                 listUser·p0.999:  27.542 ms/op
                 listUser·p0.9999: 30.525 ms/op
                 listUser·p1.00:   32.440 ms/op

Iteration   2: 7.001 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   8.831 ms/op
                 listUser·p0.95:   10.207 ms/op
                 listUser·p0.99:   14.926 ms/op
                 listUser·p0.999:  32.188 ms/op
                 listUser·p0.9999: 37.076 ms/op
                 listUser·p1.00:   37.552 ms/op

Iteration   3: 6.898 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.335 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.863 ms/op
                 listUser·p0.99:   13.451 ms/op
                 listUser·p0.999:  28.125 ms/op
                 listUser·p0.9999: 35.151 ms/op
                 listUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136514
  mean =      7.030 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 2903 
    [ 5.000,  7.500) = 100886 
    [ 7.500, 10.000) = 24614 
    [10.000, 12.500) = 5183 
    [12.500, 15.000) = 1859 
    [15.000, 17.500) = 526 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      6.488 ms/op
     p(90.0000) =      8.929 ms/op
     p(95.0000) =     10.355 ms/op
     p(99.0000) =     14.418 ms/op
     p(99.9000) =     29.507 ms/op
     p(99.9900) =     36.045 ms/op
     p(99.9990) =     37.528 ms/op
     p(99.9999) =     37.552 ms/op
    p(100.0000) =     37.552 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.015 ± 1.502  ops/ms
ClientPb.existUser                       thrpt       3   5.487 ± 1.738  ops/ms
ClientPb.getUser                         thrpt       3   5.159 ± 1.528  ops/ms
ClientPb.listUser                        thrpt       3   4.359 ± 0.591  ops/ms
ClientPb.createUser                       avgt       3   6.115 ± 2.749   ms/op
ClientPb.existUser                        avgt       3   5.834 ± 3.276   ms/op
ClientPb.getUser                          avgt       3   6.298 ± 4.277   ms/op
ClientPb.listUser                         avgt       3   7.249 ± 3.009   ms/op
ClientPb.createUser                     sample  157955   6.074 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.800           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.636           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.823           ms/op
ClientPb.createUser:createUser·p0.95    sample           9.093           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.534           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.692           ms/op
ClientPb.createUser:createUser·p0.9999  sample          37.653           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.713           ms/op
ClientPb.existUser                      sample  166178   5.776 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.281           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.528           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.651           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.682           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.169           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.095           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.916           ms/op
ClientPb.getUser                        sample  162299   5.908 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.593           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.749           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.551           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.881           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.689           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  136514   7.030 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.488           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.355           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.418           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.507           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.045           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.552           ms/op
