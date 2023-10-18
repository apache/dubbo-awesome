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
# Warmup Iteration   1: 1.565 ops/ms
# Warmup Iteration   2: 3.401 ops/ms
# Warmup Iteration   3: 6.377 ops/ms
Iteration   1: 7.417 ops/ms
Iteration   2: 7.787 ops/ms
Iteration   3: 7.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.562 ±(99.9%) 3.597 ops/ms [Average]
  (min, avg, max) = (7.417, 7.562, 7.787), stdev = 0.197
  CI (99.9%): [3.965, 11.159] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 7.056 ops/ms
# Warmup Iteration   3: 7.398 ops/ms
Iteration   1: 8.025 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.984 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (7.948, 7.984, 8.025), stdev = 0.039
  CI (99.9%): [7.278, 8.691] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 6.106 ops/ms
# Warmup Iteration   3: 7.785 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 7.745 ops/ms
Iteration   3: 8.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.863 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (7.745, 7.863, 8.020), stdev = 0.142
  CI (99.9%): [5.280, 10.447] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.017 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 6.468 ops/ms
Iteration   1: 6.447 ops/ms
Iteration   2: 6.544 ops/ms
Iteration   3: 6.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.589 ±(99.9%) 3.080 ops/ms [Average]
  (min, avg, max) = (6.447, 6.589, 6.776), stdev = 0.169
  CI (99.9%): [3.509, 9.669] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.234 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.784 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.373 ±(99.9%) 0.007 ms/op
Iteration   1: 4.072 ±(99.9%) 0.008 ms/op
Iteration   2: 4.126 ±(99.9%) 0.005 ms/op
Iteration   3: 3.977 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.058 ±(99.9%) 1.382 ms/op [Average]
  (min, avg, max) = (3.977, 4.058, 4.126), stdev = 0.076
  CI (99.9%): [2.676, 5.440] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.640 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.690 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.885 ±(99.9%) 0.007 ms/op
Iteration   1: 3.808 ±(99.9%) 0.006 ms/op
Iteration   2: 3.939 ±(99.9%) 0.007 ms/op
Iteration   3: 4.068 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.938 ±(99.9%) 2.374 ms/op [Average]
  (min, avg, max) = (3.808, 3.938, 4.068), stdev = 0.130
  CI (99.9%): [1.564, 6.313] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.268 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.522 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.003 ms/op
Iteration   1: 4.158 ±(99.9%) 0.006 ms/op
Iteration   2: 4.037 ±(99.9%) 0.005 ms/op
Iteration   3: 4.108 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.101 ±(99.9%) 1.108 ms/op [Average]
  (min, avg, max) = (4.037, 4.101, 4.158), stdev = 0.061
  CI (99.9%): [2.993, 5.209] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 15.754 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.816 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.986 ±(99.9%) 0.007 ms/op
Iteration   1: 4.799 ±(99.9%) 0.011 ms/op
Iteration   2: 4.673 ±(99.9%) 0.015 ms/op
Iteration   3: 4.876 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.783 ±(99.9%) 1.870 ms/op [Average]
  (min, avg, max) = (4.673, 4.783, 4.876), stdev = 0.103
  CI (99.9%): [2.913, 6.653] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.743 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.354 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.021 ms/op
Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.120 ms/op
                 createUser·p0.99:   7.545 ms/op
                 createUser·p0.999:  23.658 ms/op
                 createUser·p0.9999: 25.828 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 4.041 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.583 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  19.443 ms/op
                 createUser·p0.9999: 27.528 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 4.020 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.118 ms/op
                 createUser·p0.999:  28.650 ms/op
                 createUser·p0.9999: 34.079 ms/op
                 createUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237599
  mean =      4.036 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 348 
    [ 2.500,  5.000) = 224313 
    [ 5.000,  7.500) = 10899 
    [ 7.500, 10.000) = 1323 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 76 
    [27.500, 30.000) = 66 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     33.199 ms/op
     p(99.9990) =     37.093 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 12.077 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.119 ±(99.9%) 0.012 ms/op
Iteration   1: 3.822 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  21.012 ms/op
                 existUser·p0.9999: 24.105 ms/op
                 existUser·p1.00:   24.674 ms/op

Iteration   2: 3.979 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.595 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   7.963 ms/op
                 existUser·p0.999:  12.992 ms/op
                 existUser·p0.9999: 26.411 ms/op
                 existUser·p1.00:   29.721 ms/op

Iteration   3: 3.768 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  19.661 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249043
  mean =      3.854 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 446 
    [ 2.500,  5.000) = 238173 
    [ 5.000,  7.500) = 7852 
    [ 7.500, 10.000) = 1778 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     19.613 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 13.050 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.850 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.016 ms/op
Iteration   1: 4.195 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.878 ms/op
                 getUser·p0.50:   3.953 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  24.634 ms/op
                 getUser·p0.9999: 26.514 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 4.126 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  15.590 ms/op
                 getUser·p0.9999: 31.850 ms/op
                 getUser·p1.00:   33.948 ms/op

Iteration   3: 4.105 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.058 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.300 ms/op
                 getUser·p0.99:   8.380 ms/op
                 getUser·p0.999:  12.242 ms/op
                 getUser·p0.9999: 32.527 ms/op
                 getUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231641
  mean =      4.142 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 215849 
    [ 5.000,  7.500) = 11557 
    [ 7.500, 10.000) = 2809 
    [10.000, 12.500) = 805 
    [12.500, 15.000) = 200 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     23.113 ms/op
     p(99.9900) =     31.850 ms/op
     p(99.9990) =     32.989 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 15.317 ±(99.9%) 0.229 ms/op
# Warmup Iteration   2: 5.573 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.000 ±(99.9%) 0.018 ms/op
Iteration   1: 4.850 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   4.653 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  25.591 ms/op
                 listUser·p0.9999: 27.151 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 4.848 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.246 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  18.518 ms/op
                 listUser·p0.9999: 25.048 ms/op
                 listUser·p1.00:   25.395 ms/op

Iteration   3: 4.716 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.716 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199700
  mean =      4.804 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 161333 
    [ 5.000,  7.500) = 32908 
    [ 7.500, 10.000) = 3865 
    [10.000, 12.500) = 686 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 163 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 83 

  Percentiles, ms/op:
      p(0.0000) =      1.753 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      9.290 ms/op
     p(99.9000) =     19.385 ms/op
     p(99.9900) =     26.641 ms/op
     p(99.9990) =     27.657 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.562 ± 3.597  ops/ms
ClientPb.existUser                       thrpt       3   7.984 ± 0.706  ops/ms
ClientPb.getUser                         thrpt       3   7.863 ± 2.583  ops/ms
ClientPb.listUser                        thrpt       3   6.589 ± 3.080  ops/ms
ClientPb.createUser                       avgt       3   4.058 ± 1.382   ms/op
ClientPb.existUser                        avgt       3   3.938 ± 2.374   ms/op
ClientPb.getUser                          avgt       3   4.101 ± 1.108   ms/op
ClientPb.listUser                         avgt       3   4.783 ± 1.870   ms/op
ClientPb.createUser                     sample  237599   4.036 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.583           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.863           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.117           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.199           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.159           ms/op
ClientPb.existUser                      sample  249043   3.854 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.518           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.317           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.561           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.613           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.919           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.721           ms/op
ClientPb.getUser                        sample  231641   4.142 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.878           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.751           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.634           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.113           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.850           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.948           ms/op
ClientPb.listUser                       sample  199700   4.804 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.753           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.890           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.290           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.385           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.641           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
