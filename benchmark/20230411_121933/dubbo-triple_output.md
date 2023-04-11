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
# Warmup Iteration   1: 2.234 ops/ms
# Warmup Iteration   2: 5.572 ops/ms
# Warmup Iteration   3: 8.529 ops/ms
Iteration   1: 9.242 ops/ms
Iteration   2: 9.598 ops/ms
Iteration   3: 8.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.271 ±(99.9%) 5.713 ops/ms [Average]
  (min, avg, max) = (8.973, 9.271, 9.598), stdev = 0.313
  CI (99.9%): [3.558, 14.984] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.129 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 9.438 ops/ms
Iteration   1: 9.473 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.344 ±(99.9%) 2.079 ops/ms [Average]
  (min, avg, max) = (9.255, 9.344, 9.473), stdev = 0.114
  CI (99.9%): [7.265, 11.423] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.956 ops/ms
# Warmup Iteration   2: 8.501 ops/ms
# Warmup Iteration   3: 9.273 ops/ms
Iteration   1: 9.341 ops/ms
Iteration   2: 9.523 ops/ms
Iteration   3: 9.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.445 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (9.341, 9.445, 9.523), stdev = 0.093
  CI (99.9%): [7.741, 11.148] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.767 ops/ms
# Warmup Iteration   2: 7.335 ops/ms
# Warmup Iteration   3: 7.980 ops/ms
Iteration   1: 7.992 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.064 ±(99.9%) 2.148 ops/ms [Average]
  (min, avg, max) = (7.992, 8.064, 8.200), stdev = 0.118
  CI (99.9%): [5.917, 10.212] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.700 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.006 ms/op
Iteration   1: 3.413 ±(99.9%) 0.005 ms/op
Iteration   2: 3.364 ±(99.9%) 0.012 ms/op
Iteration   3: 3.519 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.432 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.364, 3.432, 3.519), stdev = 0.079
  CI (99.9%): [1.987, 4.876] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.589 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.005 ms/op
Iteration   1: 3.185 ±(99.9%) 0.004 ms/op
Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
Iteration   3: 3.281 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.219 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.185, 3.219, 3.281), stdev = 0.054
  CI (99.9%): [2.232, 4.206] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.769 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.003 ms/op
Iteration   1: 3.535 ±(99.9%) 0.003 ms/op
Iteration   2: 3.385 ±(99.9%) 0.004 ms/op
Iteration   3: 3.370 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.430 ±(99.9%) 1.662 ms/op [Average]
  (min, avg, max) = (3.370, 3.430, 3.535), stdev = 0.091
  CI (99.9%): [1.767, 5.092] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.318 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.007 ms/op
Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
Iteration   2: 3.948 ±(99.9%) 0.007 ms/op
Iteration   3: 3.912 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.948 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (3.912, 3.948, 3.985), stdev = 0.037
  CI (99.9%): [3.277, 4.620] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.536 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.571 ±(99.9%) 0.011 ms/op
Iteration   1: 3.472 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   6.142 ms/op
                 createUser·p0.999:  19.939 ms/op
                 createUser·p0.9999: 22.891 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   2: 3.393 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  21.553 ms/op
                 createUser·p0.9999: 29.346 ms/op
                 createUser·p1.00:   32.440 ms/op

Iteration   3: 3.392 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  17.486 ms/op
                 createUser·p0.9999: 30.376 ms/op
                 createUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280565
  mean =      3.419 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10996 
    [ 2.500,  5.000) = 263344 
    [ 5.000,  7.500) = 5251 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     17.925 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     31.528 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 8.545 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.018 ms/op
Iteration   1: 3.297 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.317 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  9.650 ms/op
                 existUser·p0.9999: 25.218 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  15.009 ms/op
                 existUser·p0.9999: 29.102 ms/op
                 existUser·p1.00:   29.819 ms/op

Iteration   3: 3.242 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.501 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  15.296 ms/op
                 existUser·p0.9999: 26.420 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294522
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8176 
    [ 2.500,  5.000) = 280366 
    [ 5.000,  7.500) = 4642 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.317 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     15.024 ms/op
     p(99.9900) =     27.918 ms/op
     p(99.9990) =     29.722 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 9.236 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.011 ms/op
Iteration   1: 3.527 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  20.677 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   26.542 ms/op

Iteration   2: 3.339 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   5.694 ms/op
                 getUser·p0.999:  23.043 ms/op
                 getUser·p0.9999: 30.947 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 3.479 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.020 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.125 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 26.978 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278497
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9177 
    [ 2.500,  5.000) = 261191 
    [ 5.000,  7.500) = 7311 
    [ 7.500, 10.000) = 496 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     29.042 ms/op
     p(99.9990) =     32.080 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 12.216 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.013 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.563 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 22.989 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 4.076 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.017 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.313 ms/op
                 listUser·p0.999:  17.597 ms/op
                 listUser·p0.9999: 25.887 ms/op
                 listUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240110
  mean =      3.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 230826 
    [ 5.000,  7.500) = 6596 
    [ 7.500, 10.000) = 1869 
    [10.000, 12.500) = 288 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.271 ± 5.713  ops/ms
ClientPb.existUser                       thrpt       3   9.344 ± 2.079  ops/ms
ClientPb.getUser                         thrpt       3   9.445 ± 1.703  ops/ms
ClientPb.listUser                        thrpt       3   8.064 ± 2.148  ops/ms
ClientPb.createUser                       avgt       3   3.432 ± 1.445   ms/op
ClientPb.existUser                        avgt       3   3.219 ± 0.987   ms/op
ClientPb.getUser                          avgt       3   3.430 ± 1.662   ms/op
ClientPb.listUser                         avgt       3   3.948 ± 0.672   ms/op
ClientPb.createUser                     sample  280565   3.419 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.925           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.819           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.440           ms/op
ClientPb.existUser                      sample  294522   3.258 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.317           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.527           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.024           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.918           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.819           ms/op
ClientPb.getUser                        sample  278497   3.447 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.020           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.026           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.042           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  240110   3.994 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.434           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.335           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.952           ms/op
