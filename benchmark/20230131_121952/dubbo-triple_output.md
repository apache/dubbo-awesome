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
# Warmup Iteration   1: 1.742 ops/ms
# Warmup Iteration   2: 3.645 ops/ms
# Warmup Iteration   3: 7.267 ops/ms
Iteration   1: 7.266 ops/ms
Iteration   2: 8.133 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.852 ±(99.9%) 9.267 ops/ms [Average]
  (min, avg, max) = (7.266, 7.852, 8.159), stdev = 0.508
  CI (99.9%): [≈ 0, 17.119] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.431 ops/ms
# Warmup Iteration   2: 6.674 ops/ms
# Warmup Iteration   3: 8.273 ops/ms
Iteration   1: 8.109 ops/ms
Iteration   2: 8.093 ops/ms
Iteration   3: 8.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.109 ±(99.9%) 0.287 ops/ms [Average]
  (min, avg, max) = (8.093, 8.109, 8.125), stdev = 0.016
  CI (99.9%): [7.823, 8.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 6.500 ops/ms
# Warmup Iteration   3: 7.874 ops/ms
Iteration   1: 7.829 ops/ms
Iteration   2: 7.386 ops/ms
Iteration   3: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.765 ±(99.9%) 6.410 ops/ms [Average]
  (min, avg, max) = (7.386, 7.765, 8.080), stdev = 0.351
  CI (99.9%): [1.355, 14.175] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.136 ops/ms
# Warmup Iteration   2: 5.388 ops/ms
# Warmup Iteration   3: 6.525 ops/ms
Iteration   1: 6.798 ops/ms
Iteration   2: 6.900 ops/ms
Iteration   3: 7.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.974 ±(99.9%) 4.068 ops/ms [Average]
  (min, avg, max) = (6.798, 6.974, 7.225), stdev = 0.223
  CI (99.9%): [2.906, 11.043] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.899 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.632 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.314 ±(99.9%) 0.006 ms/op
Iteration   1: 4.150 ±(99.9%) 0.007 ms/op
Iteration   2: 4.184 ±(99.9%) 0.008 ms/op
Iteration   3: 4.118 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.151 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (4.118, 4.151, 4.184), stdev = 0.033
  CI (99.9%): [3.548, 4.754] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 13.252 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.005 ms/op
Iteration   1: 4.119 ±(99.9%) 0.008 ms/op
Iteration   2: 3.898 ±(99.9%) 0.008 ms/op
Iteration   3: 4.000 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.005 ±(99.9%) 2.016 ms/op [Average]
  (min, avg, max) = (3.898, 4.005, 4.119), stdev = 0.110
  CI (99.9%): [1.989, 6.021] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.481 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.036 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.006 ms/op
Iteration   1: 4.282 ±(99.9%) 0.006 ms/op
Iteration   2: 3.962 ±(99.9%) 0.005 ms/op
Iteration   3: 3.923 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.056 ±(99.9%) 3.590 ms/op [Average]
  (min, avg, max) = (3.923, 4.056, 4.282), stdev = 0.197
  CI (99.9%): [0.466, 7.646] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.866 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.610 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.006 ms/op
Iteration   1: 4.807 ±(99.9%) 0.008 ms/op
Iteration   2: 4.816 ±(99.9%) 0.010 ms/op
Iteration   3: 4.895 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.839 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (4.807, 4.839, 4.895), stdev = 0.048
  CI (99.9%): [3.961, 5.717] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 12.738 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 5.155 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.564 ±(99.9%) 0.019 ms/op
Iteration   1: 4.197 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.946 ms/op
                 createUser·p0.50:   3.916 ms/op
                 createUser·p0.90:   4.989 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   8.200 ms/op
                 createUser·p0.999:  13.500 ms/op
                 createUser·p0.9999: 27.308 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   2: 4.245 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.980 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  24.904 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   3: 4.282 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.870 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   8.094 ms/op
                 createUser·p0.999:  20.295 ms/op
                 createUser·p0.9999: 27.951 ms/op
                 createUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 226178
  mean =      4.241 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 313 
    [ 2.500,  5.000) = 202538 
    [ 5.000,  7.500) = 19524 
    [ 7.500, 10.000) = 2722 
    [10.000, 12.500) = 577 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 140 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     20.659 ms/op
     p(99.9900) =     27.374 ms/op
     p(99.9990) =     28.539 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.005 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
Iteration   1: 4.052 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.871 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 25.169 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   2: 4.105 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.636 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   8.141 ms/op
                 existUser·p0.999:  24.969 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   3: 3.969 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   8.339 ms/op
                 existUser·p0.999:  15.794 ms/op
                 existUser·p0.9999: 33.514 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 237611
  mean =      4.041 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 210 
    [ 2.500,  5.000) = 220738 
    [ 5.000,  7.500) = 12722 
    [ 7.500, 10.000) = 3010 
    [10.000, 12.500) = 509 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.636 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     15.842 ms/op
     p(99.9900) =     31.850 ms/op
     p(99.9990) =     34.185 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.503 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.873 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.379 ±(99.9%) 0.018 ms/op
Iteration   1: 4.049 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.186 ms/op
                 getUser·p0.99:   8.267 ms/op
                 getUser·p0.999:  26.575 ms/op
                 getUser·p0.9999: 31.544 ms/op
                 getUser·p1.00:   32.866 ms/op

Iteration   2: 4.176 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.972 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  13.606 ms/op
                 getUser·p0.9999: 27.613 ms/op
                 getUser·p1.00:   28.934 ms/op

Iteration   3: 3.977 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   7.717 ms/op
                 getUser·p0.999:  28.691 ms/op
                 getUser·p0.9999: 34.275 ms/op
                 getUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235960
  mean =      4.065 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 219389 
    [ 5.000,  7.500) = 13177 
    [ 7.500, 10.000) = 2317 
    [10.000, 12.500) = 494 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 63 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.200 ms/op
     p(99.9000) =     25.003 ms/op
     p(99.9900) =     33.843 ms/op
     p(99.9990) =     34.776 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.438 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 6.156 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.847 ±(99.9%) 0.018 ms/op
Iteration   1: 4.768 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  27.624 ms/op
                 listUser·p0.9999: 31.916 ms/op
                 listUser·p1.00:   32.932 ms/op

Iteration   2: 4.784 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  19.927 ms/op
                 listUser·p0.9999: 25.766 ms/op
                 listUser·p1.00:   26.083 ms/op

Iteration   3: 4.762 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  20.608 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200964
  mean =      4.771 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 168620 
    [ 5.000,  7.500) = 27238 
    [ 7.500, 10.000) = 4005 
    [10.000, 12.500) = 525 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.466 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     21.266 ms/op
     p(99.9900) =     30.927 ms/op
     p(99.9990) =     32.800 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.852 ± 9.267  ops/ms
ClientPb.existUser                       thrpt       3   8.109 ± 0.287  ops/ms
ClientPb.getUser                         thrpt       3   7.765 ± 6.410  ops/ms
ClientPb.listUser                        thrpt       3   6.974 ± 4.068  ops/ms
ClientPb.createUser                       avgt       3   4.151 ± 0.603   ms/op
ClientPb.existUser                        avgt       3   4.005 ± 2.016   ms/op
ClientPb.getUser                          avgt       3   4.056 ± 3.590   ms/op
ClientPb.listUser                         avgt       3   4.839 ± 0.878   ms/op
ClientPb.createUser                     sample  226178   4.241 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.540           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.536           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.659           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.374           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.738           ms/op
ClientPb.existUser                      sample  237611   4.041 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.636           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.620           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.380           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.842           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.850           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  235960   4.065 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.403           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.661           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.464           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.200           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.003           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.843           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.914           ms/op
ClientPb.listUser                       sample  200964   4.771 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.466           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.266           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.927           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.932           ms/op
