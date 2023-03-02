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
# Warmup Iteration   1: 1.577 ops/ms
# Warmup Iteration   2: 3.866 ops/ms
# Warmup Iteration   3: 7.248 ops/ms
Iteration   1: 7.077 ops/ms
Iteration   2: 7.789 ops/ms
Iteration   3: 7.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.543 ±(99.9%) 7.368 ops/ms [Average]
  (min, avg, max) = (7.077, 7.543, 7.789), stdev = 0.404
  CI (99.9%): [0.175, 14.911] (assumes normal distribution)


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
# Warmup Iteration   1: 2.448 ops/ms
# Warmup Iteration   2: 6.852 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.294 ops/ms
Iteration   2: 8.495 ops/ms
Iteration   3: 7.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.262 ±(99.9%) 4.579 ops/ms [Average]
  (min, avg, max) = (7.996, 8.262, 8.495), stdev = 0.251
  CI (99.9%): [3.683, 12.841] (assumes normal distribution)


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
# Warmup Iteration   1: 2.379 ops/ms
# Warmup Iteration   2: 5.989 ops/ms
# Warmup Iteration   3: 7.682 ops/ms
Iteration   1: 7.835 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.028 ±(99.9%) 5.808 ops/ms [Average]
  (min, avg, max) = (7.835, 8.028, 8.396), stdev = 0.318
  CI (99.9%): [2.220, 13.837] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.085 ops/ms
# Warmup Iteration   2: 5.882 ops/ms
# Warmup Iteration   3: 6.742 ops/ms
Iteration   1: 6.839 ops/ms
Iteration   2: 7.012 ops/ms
Iteration   3: 6.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.870 ±(99.9%) 2.362 ops/ms [Average]
  (min, avg, max) = (6.758, 6.870, 7.012), stdev = 0.129
  CI (99.9%): [4.507, 9.232] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.681 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.897 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.267 ±(99.9%) 0.005 ms/op
Iteration   1: 3.847 ±(99.9%) 0.014 ms/op
Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
Iteration   3: 4.000 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.938 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (3.847, 3.938, 4.000), stdev = 0.081
  CI (99.9%): [2.459, 5.418] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.637 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.005 ms/op
Iteration   1: 3.935 ±(99.9%) 0.005 ms/op
Iteration   2: 3.774 ±(99.9%) 0.004 ms/op
Iteration   3: 3.782 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.830 ±(99.9%) 1.654 ms/op [Average]
  (min, avg, max) = (3.774, 3.830, 3.935), stdev = 0.091
  CI (99.9%): [2.177, 5.484] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.807 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.003 ms/op
Iteration   1: 4.055 ±(99.9%) 0.006 ms/op
Iteration   2: 3.970 ±(99.9%) 0.009 ms/op
Iteration   3: 4.286 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.104 ±(99.9%) 2.982 ms/op [Average]
  (min, avg, max) = (3.970, 4.104, 4.286), stdev = 0.163
  CI (99.9%): [1.121, 7.086] (assumes normal distribution)


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
# Warmup Iteration   1: 13.460 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.478 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.007 ms/op
Iteration   1: 4.563 ±(99.9%) 0.014 ms/op
Iteration   2: 4.530 ±(99.9%) 0.012 ms/op
Iteration   3: 4.584 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.559 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (4.530, 4.559, 4.584), stdev = 0.027
  CI (99.9%): [4.065, 5.053] (assumes normal distribution)


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
# Warmup Iteration   1: 11.591 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 5.272 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.019 ms/op
Iteration   1: 3.971 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.970 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  11.590 ms/op
                 createUser·p0.9999: 25.424 ms/op
                 createUser·p1.00:   26.214 ms/op

Iteration   2: 4.106 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.911 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   8.110 ms/op
                 createUser·p0.999:  25.087 ms/op
                 createUser·p0.9999: 28.248 ms/op
                 createUser·p1.00:   29.098 ms/op

Iteration   3: 3.891 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  12.763 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 240571
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 314 
    [ 2.500,  5.000) = 227175 
    [ 5.000,  7.500) = 10793 
    [ 7.500, 10.000) = 1652 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      7.414 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     30.372 ms/op
     p(99.9990) =     31.771 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 11.594 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
Iteration   1: 4.041 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   7.823 ms/op
                 existUser·p0.999:  23.618 ms/op
                 existUser·p0.9999: 41.681 ms/op
                 existUser·p1.00:   41.746 ms/op

Iteration   2: 3.765 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  12.624 ms/op
                 existUser·p0.9999: 28.655 ms/op
                 existUser·p1.00:   30.310 ms/op

Iteration   3: 3.892 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.796 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.873 ms/op
                 existUser·p0.999:  13.124 ms/op
                 existUser·p0.9999: 32.482 ms/op
                 existUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246392
  mean =      3.896 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 234148 
    [ 5.000, 10.000) = 11694 
    [10.000, 15.000) = 299 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 94 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     39.738 ms/op
     p(99.9990) =     41.746 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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
# Warmup Iteration   1: 11.729 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.941 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.014 ms/op
Iteration   1: 3.953 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.965 ms/op
                 getUser·p0.999:  24.545 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   7.226 ms/op
                 getUser·p0.999:  10.431 ms/op
                 getUser·p0.9999: 27.993 ms/op
                 getUser·p1.00:   29.032 ms/op

Iteration   3: 3.899 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.423 ms/op
                 getUser·p0.999:  27.951 ms/op
                 getUser·p0.9999: 31.792 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242654
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 231505 
    [ 5.000,  7.500) = 9312 
    [ 7.500, 10.000) = 1246 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 42 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     24.522 ms/op
     p(99.9900) =     30.815 ms/op
     p(99.9990) =     32.885 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 14.108 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.918 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.002 ±(99.9%) 0.019 ms/op
Iteration   1: 4.851 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.626 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   6.187 ms/op
                 listUser·p0.99:   9.415 ms/op
                 listUser·p0.999:  24.250 ms/op
                 listUser·p0.9999: 34.447 ms/op
                 listUser·p1.00:   35.455 ms/op

Iteration   2: 4.667 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.682 ms/op
                 listUser·p0.999:  20.906 ms/op
                 listUser·p0.9999: 26.277 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   3: 4.583 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  17.705 ms/op
                 listUser·p0.9999: 26.542 ms/op
                 listUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 204131
  mean =      4.698 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 176502 
    [ 5.000,  7.500) = 23037 
    [ 7.500, 10.000) = 3254 
    [10.000, 12.500) = 691 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     32.687 ms/op
     p(99.9990) =     35.389 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.543 ± 7.368  ops/ms
ClientPb.existUser                       thrpt       3   8.262 ± 4.579  ops/ms
ClientPb.getUser                         thrpt       3   8.028 ± 5.808  ops/ms
ClientPb.listUser                        thrpt       3   6.870 ± 2.362  ops/ms
ClientPb.createUser                       avgt       3   3.938 ± 1.480   ms/op
ClientPb.existUser                        avgt       3   3.830 ± 1.654   ms/op
ClientPb.getUser                          avgt       3   4.104 ± 2.982   ms/op
ClientPb.listUser                         avgt       3   4.559 ± 0.494   ms/op
ClientPb.createUser                     sample  240571   3.987 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.087           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.414           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.372           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.850           ms/op
ClientPb.existUser                      sample  246392   3.896 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.796           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.997           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.291           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.483           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.738           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.746           ms/op
ClientPb.getUser                        sample  242654   3.954 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.389           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.846           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.914           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.522           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.815           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  204131   4.698 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.786           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.929           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.053           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.687           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.455           ms/op
