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
# Warmup Iteration   1: 1.439 ops/ms
# Warmup Iteration   2: 3.186 ops/ms
# Warmup Iteration   3: 7.031 ops/ms
Iteration   1: 7.312 ops/ms
Iteration   2: 7.303 ops/ms
Iteration   3: 7.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.394 ±(99.9%) 2.721 ops/ms [Average]
  (min, avg, max) = (7.303, 7.394, 7.566), stdev = 0.149
  CI (99.9%): [4.672, 10.115] (assumes normal distribution)


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
# Warmup Iteration   1: 1.949 ops/ms
# Warmup Iteration   2: 6.509 ops/ms
# Warmup Iteration   3: 7.925 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 8.052 ops/ms
Iteration   3: 8.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.048 ±(99.9%) 0.576 ops/ms [Average]
  (min, avg, max) = (8.015, 8.048, 8.078), stdev = 0.032
  CI (99.9%): [7.472, 8.625] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 5.733 ops/ms
# Warmup Iteration   3: 7.698 ops/ms
Iteration   1: 7.707 ops/ms
Iteration   2: 7.931 ops/ms
Iteration   3: 7.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.785 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (7.707, 7.785, 7.931), stdev = 0.127
  CI (99.9%): [5.476, 10.094] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.951 ops/ms
# Warmup Iteration   2: 5.307 ops/ms
# Warmup Iteration   3: 6.262 ops/ms
Iteration   1: 6.551 ops/ms
Iteration   2: 6.553 ops/ms
Iteration   3: 6.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.573 ±(99.9%) 0.651 ops/ms [Average]
  (min, avg, max) = (6.551, 6.573, 6.614), stdev = 0.036
  CI (99.9%): [5.922, 7.223] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.628 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.788 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.005 ms/op
Iteration   1: 4.059 ±(99.9%) 0.006 ms/op
Iteration   2: 4.160 ±(99.9%) 0.009 ms/op
Iteration   3: 4.226 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.148 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (4.059, 4.148, 4.226), stdev = 0.085
  CI (99.9%): [2.606, 5.690] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.497 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.006 ms/op
Iteration   1: 4.031 ±(99.9%) 0.006 ms/op
Iteration   2: 4.010 ±(99.9%) 0.005 ms/op
Iteration   3: 3.890 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.977 ±(99.9%) 1.387 ms/op [Average]
  (min, avg, max) = (3.890, 3.977, 4.031), stdev = 0.076
  CI (99.9%): [2.590, 5.364] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.114 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.600 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.006 ms/op
Iteration   1: 4.492 ±(99.9%) 0.006 ms/op
Iteration   2: 4.121 ±(99.9%) 0.006 ms/op
Iteration   3: 4.227 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.280 ±(99.9%) 3.491 ms/op [Average]
  (min, avg, max) = (4.121, 4.280, 4.492), stdev = 0.191
  CI (99.9%): [0.789, 7.771] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 17.417 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.042 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.933 ±(99.9%) 0.006 ms/op
Iteration   1: 4.887 ±(99.9%) 0.007 ms/op
Iteration   2: 4.791 ±(99.9%) 0.012 ms/op
Iteration   3: 4.736 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.805 ±(99.9%) 1.395 ms/op [Average]
  (min, avg, max) = (4.736, 4.805, 4.887), stdev = 0.076
  CI (99.9%): [3.409, 6.200] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.126 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.906 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.583 ±(99.9%) 0.018 ms/op
Iteration   1: 4.117 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.698 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.177 ms/op
                 createUser·p0.99:   7.291 ms/op
                 createUser·p0.999:  21.725 ms/op
                 createUser·p0.9999: 24.420 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 4.288 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.612 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.030 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  13.321 ms/op
                 createUser·p0.9999: 25.847 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   3: 4.036 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  17.808 ms/op
                 createUser·p0.9999: 28.054 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 231416
  mean =      4.144 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 340 
    [ 2.500,  5.000) = 213878 
    [ 5.000,  7.500) = 15043 
    [ 7.500, 10.000) = 1374 
    [10.000, 12.500) = 417 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.339 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     27.193 ms/op
     p(99.9990) =     28.534 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.841 ±(99.9%) 0.156 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.270 ±(99.9%) 0.013 ms/op
Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.505 ms/op
                 existUser·p0.99:   7.799 ms/op
                 existUser·p0.999:  12.894 ms/op
                 existUser·p0.9999: 30.474 ms/op
                 existUser·p1.00:   31.031 ms/op

Iteration   2: 4.278 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.894 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.710 ms/op
                 existUser·p0.99:   8.167 ms/op
                 existUser·p0.999:  25.107 ms/op
                 existUser·p0.9999: 29.082 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 4.009 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.937 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  21.003 ms/op
                 existUser·p0.9999: 30.180 ms/op
                 existUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 232005
  mean =      4.135 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 216 
    [ 2.500,  5.000) = 212776 
    [ 5.000,  7.500) = 16001 
    [ 7.500, 10.000) = 2187 
    [10.000, 12.500) = 404 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     30.238 ms/op
     p(99.9990) =     30.989 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.467 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.015 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.571 ±(99.9%) 0.021 ms/op
Iteration   1: 4.313 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   4.043 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   9.073 ms/op
                 getUser·p0.999:  22.502 ms/op
                 getUser·p0.9999: 24.159 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 4.240 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   8.651 ms/op
                 getUser·p0.999:  24.288 ms/op
                 getUser·p0.9999: 30.978 ms/op
                 getUser·p1.00:   32.899 ms/op

Iteration   3: 4.082 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.873 ms/op
                 getUser·p0.999:  17.819 ms/op
                 getUser·p0.9999: 27.787 ms/op
                 getUser·p1.00:   31.818 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 228073
  mean =      4.210 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 211656 
    [ 5.000,  7.500) = 11265 
    [ 7.500, 10.000) = 3933 
    [10.000, 12.500) = 528 
    [12.500, 15.000) = 244 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     22.610 ms/op
     p(99.9900) =     29.661 ms/op
     p(99.9990) =     32.825 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 15.189 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.733 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.973 ±(99.9%) 0.016 ms/op
Iteration   1: 5.075 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  23.527 ms/op
                 listUser·p0.9999: 25.772 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   2: 4.933 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.757 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.562 ms/op
                 listUser·p0.99:   9.948 ms/op
                 listUser·p0.999:  19.366 ms/op
                 listUser·p0.9999: 25.957 ms/op
                 listUser·p1.00:   26.968 ms/op

Iteration   3: 4.767 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.974 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 194881
  mean =      4.922 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 144980 
    [ 5.000,  7.500) = 43104 
    [ 7.500, 10.000) = 4744 
    [10.000, 12.500) = 1087 
    [12.500, 15.000) = 382 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      4.678 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     21.369 ms/op
     p(99.9900) =     25.396 ms/op
     p(99.9990) =     26.471 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.394 ± 2.721  ops/ms
ClientPb.existUser                       thrpt       3   8.048 ± 0.576  ops/ms
ClientPb.getUser                         thrpt       3   7.785 ± 2.309  ops/ms
ClientPb.listUser                        thrpt       3   6.573 ± 0.651  ops/ms
ClientPb.createUser                       avgt       3   4.148 ± 1.542   ms/op
ClientPb.existUser                        avgt       3   3.977 ± 1.387   ms/op
ClientPb.getUser                          avgt       3   4.280 ± 3.491   ms/op
ClientPb.listUser                         avgt       3   4.805 ± 1.395   ms/op
ClientPb.createUser                     sample  231416   4.144 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.612           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.339           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.645           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.193           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.932           ms/op
ClientPb.existUser                      sample  232005   4.135 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.653           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.957           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.922           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  228073   4.210 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.921           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.782           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.610           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.661           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  194881   4.922 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.534           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.537           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.207           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.369           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.396           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.968           ms/op
