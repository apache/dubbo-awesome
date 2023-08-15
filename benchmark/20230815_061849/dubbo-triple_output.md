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
# Warmup Iteration   1: 1.137 ops/ms
# Warmup Iteration   2: 2.245 ops/ms
# Warmup Iteration   3: 4.992 ops/ms
Iteration   1: 5.600 ops/ms
Iteration   2: 5.564 ops/ms
Iteration   3: 5.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.611 ±(99.9%) 0.979 ops/ms [Average]
  (min, avg, max) = (5.564, 5.611, 5.669), stdev = 0.054
  CI (99.9%): [4.632, 6.590] (assumes normal distribution)


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
# Warmup Iteration   1: 1.586 ops/ms
# Warmup Iteration   2: 4.405 ops/ms
# Warmup Iteration   3: 5.686 ops/ms
Iteration   1: 5.627 ops/ms
Iteration   2: 5.641 ops/ms
Iteration   3: 5.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.737 ±(99.9%) 3.258 ops/ms [Average]
  (min, avg, max) = (5.627, 5.737, 5.943), stdev = 0.179
  CI (99.9%): [2.479, 8.995] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.542 ops/ms
# Warmup Iteration   2: 4.336 ops/ms
# Warmup Iteration   3: 5.756 ops/ms
Iteration   1: 5.560 ops/ms
Iteration   2: 5.662 ops/ms
Iteration   3: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.661 ±(99.9%) 1.839 ops/ms [Average]
  (min, avg, max) = (5.560, 5.661, 5.762), stdev = 0.101
  CI (99.9%): [3.822, 7.501] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.637 ops/ms
# Warmup Iteration   2: 4.172 ops/ms
# Warmup Iteration   3: 4.664 ops/ms
Iteration   1: 4.895 ops/ms
Iteration   2: 4.985 ops/ms
Iteration   3: 4.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.931 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (4.895, 4.931, 4.985), stdev = 0.048
  CI (99.9%): [4.058, 5.804] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.891 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 6.944 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.821 ±(99.9%) 0.016 ms/op
Iteration   1: 5.575 ±(99.9%) 0.012 ms/op
Iteration   2: 5.580 ±(99.9%) 0.012 ms/op
Iteration   3: 5.629 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.595 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (5.575, 5.595, 5.629), stdev = 0.030
  CI (99.9%): [5.053, 6.136] (assumes normal distribution)


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
# Warmup Iteration   1: 17.114 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.341 ±(99.9%) 0.009 ms/op
Iteration   1: 5.325 ±(99.9%) 0.014 ms/op
Iteration   2: 5.504 ±(99.9%) 0.010 ms/op
Iteration   3: 5.391 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.406 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (5.325, 5.406, 5.504), stdev = 0.090
  CI (99.9%): [3.756, 7.057] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.897 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.340 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.668 ±(99.9%) 0.012 ms/op
Iteration   1: 5.643 ±(99.9%) 0.019 ms/op
Iteration   2: 5.664 ±(99.9%) 0.016 ms/op
Iteration   3: 5.554 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.620 ±(99.9%) 1.066 ms/op [Average]
  (min, avg, max) = (5.554, 5.620, 5.664), stdev = 0.058
  CI (99.9%): [4.554, 6.687] (assumes normal distribution)


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
# Warmup Iteration   1: 17.813 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 8.533 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 6.488 ±(99.9%) 0.019 ms/op
Iteration   1: 6.642 ±(99.9%) 0.019 ms/op
Iteration   2: 6.691 ±(99.9%) 0.018 ms/op
Iteration   3: 6.442 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.592 ±(99.9%) 2.405 ms/op [Average]
  (min, avg, max) = (6.442, 6.592, 6.691), stdev = 0.132
  CI (99.9%): [4.187, 8.997] (assumes normal distribution)


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
# Warmup Iteration   1: 17.293 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 6.512 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.780 ±(99.9%) 0.026 ms/op
Iteration   1: 5.504 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.281 ms/op
                 createUser·p0.50:   5.128 ms/op
                 createUser·p0.90:   6.914 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   11.600 ms/op
                 createUser·p0.999:  24.534 ms/op
                 createUser·p0.9999: 27.799 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   2: 5.442 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.886 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.570 ms/op
                 createUser·p0.95:   7.135 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  26.059 ms/op
                 createUser·p0.9999: 29.229 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   3: 5.322 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.367 ms/op
                 createUser·p0.50:   5.071 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.217 ms/op
                 createUser·p0.99:   9.732 ms/op
                 createUser·p0.999:  28.277 ms/op
                 createUser·p0.9999: 32.113 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176906
  mean =      5.422 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 75517 
    [ 5.000,  7.500) = 92677 
    [ 7.500, 10.000) = 6500 
    [10.000, 12.500) = 1549 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 36 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.886 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.627 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =     10.453 ms/op
     p(99.9000) =     24.874 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     33.338 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 17.022 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.408 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.557 ±(99.9%) 0.023 ms/op
Iteration   1: 5.204 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.291 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  16.420 ms/op
                 existUser·p0.9999: 25.484 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   2: 5.306 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.392 ms/op
                 existUser·p0.50:   5.071 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.340 ms/op
                 existUser·p0.99:   10.158 ms/op
                 existUser·p0.999:  26.477 ms/op
                 existUser·p0.9999: 29.783 ms/op
                 existUser·p1.00:   30.147 ms/op

Iteration   3: 5.335 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   11.829 ms/op
                 existUser·p0.999:  26.623 ms/op
                 existUser·p0.9999: 30.474 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 181657
  mean =      5.281 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 90930 
    [ 5.000,  7.500) = 81915 
    [ 7.500, 10.000) = 6352 
    [10.000, 12.500) = 1511 
    [12.500, 15.000) = 573 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =     10.650 ms/op
     p(99.9000) =     23.110 ms/op
     p(99.9900) =     30.043 ms/op
     p(99.9990) =     30.839 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 16.913 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.209 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.428 ±(99.9%) 0.018 ms/op
Iteration   1: 5.539 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.568 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   6.808 ms/op
                 getUser·p0.95:   8.094 ms/op
                 getUser·p0.99:   11.662 ms/op
                 getUser·p0.999:  21.901 ms/op
                 getUser·p0.9999: 26.908 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   2: 5.461 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.774 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   6.668 ms/op
                 getUser·p0.95:   7.897 ms/op
                 getUser·p0.99:   10.895 ms/op
                 getUser·p0.999:  24.350 ms/op
                 getUser·p0.9999: 34.865 ms/op
                 getUser·p1.00:   36.307 ms/op

Iteration   3: 5.503 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.470 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.512 ms/op
                 getUser·p0.99:   10.662 ms/op
                 getUser·p0.999:  25.690 ms/op
                 getUser·p0.9999: 30.630 ms/op
                 getUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174576
  mean =      5.501 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 67520 
    [ 5.000,  7.500) = 96692 
    [ 7.500, 10.000) = 7570 
    [10.000, 12.500) = 1932 
    [12.500, 15.000) = 538 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      5.210 ms/op
     p(90.0000) =      6.685 ms/op
     p(95.0000) =      7.857 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     32.517 ms/op
     p(99.9990) =     35.818 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 19.180 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 8.143 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.730 ±(99.9%) 0.027 ms/op
Iteration   1: 6.556 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.851 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.208 ms/op
                 listUser·p0.95:   9.434 ms/op
                 listUser·p0.99:   13.097 ms/op
                 listUser·p0.999:  27.762 ms/op
                 listUser·p0.9999: 31.891 ms/op
                 listUser·p1.00:   32.211 ms/op

Iteration   2: 6.507 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   7.933 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  29.126 ms/op
                 listUser·p0.9999: 32.464 ms/op
                 listUser·p1.00:   34.800 ms/op

Iteration   3: 6.444 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.078 ms/op
                 listUser·p0.90:   7.791 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.632 ms/op
                 listUser·p0.999:  26.489 ms/op
                 listUser·p0.9999: 32.150 ms/op
                 listUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147532
  mean =      6.502 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 5978 
    [ 5.000,  7.500) = 120858 
    [ 7.500, 10.000) = 15471 
    [10.000, 12.500) = 3584 
    [12.500, 15.000) = 1076 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 107 
    [30.000, 32.500) = 71 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.302 ms/op
     p(50.0000) =      6.111 ms/op
     p(90.0000) =      7.987 ms/op
     p(95.0000) =      9.290 ms/op
     p(99.0000) =     12.698 ms/op
     p(99.9000) =     28.113 ms/op
     p(99.9900) =     32.121 ms/op
     p(99.9990) =     34.644 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.611 ± 0.979  ops/ms
ClientPb.existUser                       thrpt       3   5.737 ± 3.258  ops/ms
ClientPb.getUser                         thrpt       3   5.661 ± 1.839  ops/ms
ClientPb.listUser                        thrpt       3   4.931 ± 0.873  ops/ms
ClientPb.createUser                       avgt       3   5.595 ± 0.542   ms/op
ClientPb.existUser                        avgt       3   5.406 ± 1.651   ms/op
ClientPb.getUser                          avgt       3   5.620 ± 1.066   ms/op
ClientPb.listUser                         avgt       3   6.592 ± 2.405   ms/op
ClientPb.createUser                     sample  176906   5.422 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.627           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.471           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.453           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.874           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.802           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  181657   5.281 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.038           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.447           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.110           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.043           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.293           ms/op
ClientPb.getUser                        sample  174576   5.501 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.774           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.210           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.685           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.857           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.092           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.888           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.517           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.307           ms/op
ClientPb.listUser                       sample  147532   6.502 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.302           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.111           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.987           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.698           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.113           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.121           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.800           ms/op
