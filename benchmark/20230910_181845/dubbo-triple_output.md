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
# Warmup Iteration   1: 0.995 ops/ms
# Warmup Iteration   2: 2.061 ops/ms
# Warmup Iteration   3: 4.708 ops/ms
Iteration   1: 5.263 ops/ms
Iteration   2: 5.399 ops/ms
Iteration   3: 5.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.417 ±(99.9%) 2.972 ops/ms [Average]
  (min, avg, max) = (5.263, 5.417, 5.588), stdev = 0.163
  CI (99.9%): [2.445, 8.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.480 ops/ms
# Warmup Iteration   2: 4.217 ops/ms
# Warmup Iteration   3: 5.418 ops/ms
Iteration   1: 5.690 ops/ms
Iteration   2: 5.940 ops/ms
Iteration   3: 5.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.831 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (5.690, 5.831, 5.940), stdev = 0.128
  CI (99.9%): [3.496, 8.166] (assumes normal distribution)


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
# Warmup Iteration   1: 1.666 ops/ms
# Warmup Iteration   2: 4.580 ops/ms
# Warmup Iteration   3: 5.653 ops/ms
Iteration   1: 5.580 ops/ms
Iteration   2: 5.596 ops/ms
Iteration   3: 5.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.635 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (5.580, 5.635, 5.728), stdev = 0.081
  CI (99.9%): [4.156, 7.114] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.400 ops/ms
# Warmup Iteration   2: 3.749 ops/ms
# Warmup Iteration   3: 4.570 ops/ms
Iteration   1: 4.810 ops/ms
Iteration   2: 4.597 ops/ms
Iteration   3: 5.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.863 ±(99.9%) 5.402 ops/ms [Average]
  (min, avg, max) = (4.597, 4.863, 5.182), stdev = 0.296
  CI (99.9%): [≈ 0, 10.265] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.296 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 7.104 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.999 ±(99.9%) 0.008 ms/op
Iteration   1: 5.575 ±(99.9%) 0.018 ms/op
Iteration   2: 5.767 ±(99.9%) 0.009 ms/op
Iteration   3: 5.635 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.659 ±(99.9%) 1.787 ms/op [Average]
  (min, avg, max) = (5.575, 5.659, 5.767), stdev = 0.098
  CI (99.9%): [3.872, 7.446] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 16.756 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 7.516 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.410 ±(99.9%) 0.017 ms/op
Iteration   1: 5.406 ±(99.9%) 0.012 ms/op
Iteration   2: 5.347 ±(99.9%) 0.010 ms/op
Iteration   3: 5.359 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.370 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (5.347, 5.370, 5.406), stdev = 0.031
  CI (99.9%): [4.798, 5.943] (assumes normal distribution)


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
# Warmup Iteration   1: 18.018 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 6.482 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.008 ms/op
Iteration   1: 5.810 ±(99.9%) 0.009 ms/op
Iteration   2: 5.703 ±(99.9%) 0.013 ms/op
Iteration   3: 5.289 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.601 ±(99.9%) 5.016 ms/op [Average]
  (min, avg, max) = (5.289, 5.601, 5.810), stdev = 0.275
  CI (99.9%): [0.584, 10.617] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 17.559 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 7.147 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.162 ±(99.9%) 0.014 ms/op
Iteration   1: 6.283 ±(99.9%) 0.013 ms/op
Iteration   2: 6.182 ±(99.9%) 0.010 ms/op
Iteration   3: 6.028 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.164 ±(99.9%) 2.337 ms/op [Average]
  (min, avg, max) = (6.028, 6.164, 6.283), stdev = 0.128
  CI (99.9%): [3.828, 8.501] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 15.246 ±(99.9%) 0.249 ms/op
# Warmup Iteration   2: 5.868 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.614 ±(99.9%) 0.025 ms/op
Iteration   1: 5.317 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   7.045 ms/op
                 createUser·p0.95:   7.832 ms/op
                 createUser·p0.99:   10.371 ms/op
                 createUser·p0.999:  22.437 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 5.280 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.755 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.200 ms/op
                 createUser·p0.999:  22.410 ms/op
                 createUser·p0.9999: 30.898 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   3: 5.197 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.216 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   7.127 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  26.061 ms/op
                 createUser·p0.9999: 31.256 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182237
  mean =      5.264 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 91481 
    [ 5.000,  7.500) = 81237 
    [ 7.500, 10.000) = 7574 
    [10.000, 12.500) = 1244 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 43 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.093 ms/op
     p(99.9000) =     23.061 ms/op
     p(99.9900) =     31.024 ms/op
     p(99.9990) =     32.070 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 15.815 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.879 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.155 ±(99.9%) 0.020 ms/op
Iteration   1: 5.304 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   8.012 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  14.647 ms/op
                 existUser·p0.9999: 26.140 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   2: 5.165 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.895 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.348 ms/op
                 existUser·p0.99:   10.063 ms/op
                 existUser·p0.999:  22.712 ms/op
                 existUser·p0.9999: 39.637 ms/op
                 existUser·p1.00:   43.516 ms/op

Iteration   3: 5.008 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.921 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   6.160 ms/op
                 existUser·p0.95:   6.963 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  24.538 ms/op
                 existUser·p0.9999: 34.054 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 185934
  mean =      5.156 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 103831 
    [ 5.000, 10.000) = 80182 
    [10.000, 15.000) = 1702 
    [15.000, 20.000) = 52 
    [20.000, 25.000) = 39 
    [25.000, 30.000) = 56 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.841 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     37.632 ms/op
     p(99.9990) =     42.221 ms/op
     p(99.9999) =     43.516 ms/op
    p(100.0000) =     43.516 ms/op


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
# Warmup Iteration   1: 15.464 ±(99.9%) 0.214 ms/op
# Warmup Iteration   2: 5.911 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.408 ±(99.9%) 0.020 ms/op
Iteration   1: 5.352 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   5.038 ms/op
                 getUser·p0.90:   6.668 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   11.043 ms/op
                 getUser·p0.999:  23.651 ms/op
                 getUser·p0.9999: 27.494 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 5.310 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.680 ms/op
                 getUser·p0.99:   10.553 ms/op
                 getUser·p0.999:  22.768 ms/op
                 getUser·p0.9999: 26.601 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   3: 5.127 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.347 ms/op
                 getUser·p0.50:   4.801 ms/op
                 getUser·p0.90:   6.349 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   9.699 ms/op
                 getUser·p0.999:  25.172 ms/op
                 getUser·p0.9999: 29.065 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182283
  mean =      5.261 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 97051 
    [ 5.000,  7.500) = 76236 
    [ 7.500, 10.000) = 6653 
    [10.000, 12.500) = 1624 
    [12.500, 15.000) = 365 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.554 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.404 ms/op
     p(99.9000) =     23.527 ms/op
     p(99.9900) =     28.337 ms/op
     p(99.9990) =     29.690 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 17.847 ±(99.9%) 0.307 ms/op
# Warmup Iteration   2: 6.931 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.903 ±(99.9%) 0.023 ms/op
Iteration   1: 6.312 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.337 ms/op
                 listUser·p0.999:  24.979 ms/op
                 listUser·p0.9999: 28.101 ms/op
                 listUser·p1.00:   28.443 ms/op

Iteration   2: 5.829 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   3.232 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.241 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  25.104 ms/op
                 listUser·p0.9999: 27.870 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   3: 5.847 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.298 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  19.013 ms/op
                 listUser·p0.9999: 21.285 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 160350
  mean =      5.988 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 32927 
    [ 5.000,  7.500) = 112403 
    [ 7.500, 10.000) = 11225 
    [10.000, 12.500) = 2452 
    [12.500, 15.000) = 787 
    [15.000, 17.500) = 228 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 85 

  Percentiles, ms/op:
      p(0.0000) =      1.767 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.406 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     23.680 ms/op
     p(99.9900) =     27.753 ms/op
     p(99.9990) =     28.423 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.417 ± 2.972  ops/ms
ClientPb.existUser                       thrpt       3   5.831 ± 2.335  ops/ms
ClientPb.getUser                         thrpt       3   5.635 ± 1.479  ops/ms
ClientPb.listUser                        thrpt       3   4.863 ± 5.402  ops/ms
ClientPb.createUser                       avgt       3   5.659 ± 1.787   ms/op
ClientPb.existUser                        avgt       3   5.370 ± 0.572   ms/op
ClientPb.getUser                          avgt       3   5.601 ± 5.016   ms/op
ClientPb.listUser                         avgt       3   6.164 ± 2.337   ms/op
ClientPb.createUser                     sample  182237   5.264 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.093           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.061           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.024           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.178           ms/op
ClientPb.existUser                      sample  185934   5.156 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.895           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.841           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.554           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.496           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.060           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.024           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.632           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.516           ms/op
ClientPb.getUser                        sample  182283   5.261 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.554           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.404           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.527           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.337           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.852           ms/op
ClientPb.listUser                       sample  160350   5.988 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.767           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.157           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.753           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.443           ms/op
