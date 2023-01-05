# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.757 ops/ms
# Warmup Iteration   2: 3.739 ops/ms
# Warmup Iteration   3: 7.637 ops/ms
Iteration   1: 7.961 ops/ms
Iteration   2: 8.033 ops/ms
Iteration   3: 8.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.134 ±(99.9%) 4.382 ops/ms [Average]
  (min, avg, max) = (7.961, 8.134, 8.409), stdev = 0.240
  CI (99.9%): [3.753, 12.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.309 ops/ms
# Warmup Iteration   2: 7.030 ops/ms
# Warmup Iteration   3: 7.701 ops/ms
Iteration   1: 8.515 ops/ms
Iteration   2: 8.469 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.297 ±(99.9%) 6.182 ops/ms [Average]
  (min, avg, max) = (7.906, 8.297, 8.515), stdev = 0.339
  CI (99.9%): [2.115, 14.479] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.402 ops/ms
# Warmup Iteration   2: 6.929 ops/ms
# Warmup Iteration   3: 7.310 ops/ms
Iteration   1: 8.100 ops/ms
Iteration   2: 8.604 ops/ms
Iteration   3: 8.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.384 ±(99.9%) 4.710 ops/ms [Average]
  (min, avg, max) = (8.100, 8.384, 8.604), stdev = 0.258
  CI (99.9%): [3.674, 13.094] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.224 ops/ms
# Warmup Iteration   2: 5.701 ops/ms
# Warmup Iteration   3: 6.841 ops/ms
Iteration   1: 6.968 ops/ms
Iteration   2: 6.902 ops/ms
Iteration   3: 6.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.912 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (6.867, 6.912, 6.968), stdev = 0.051
  CI (99.9%): [5.982, 7.843] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.802 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.008 ms/op
Iteration   1: 3.786 ±(99.9%) 0.013 ms/op
Iteration   2: 3.894 ±(99.9%) 0.009 ms/op
Iteration   3: 3.892 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.857 ±(99.9%) 1.131 ms/op [Average]
  (min, avg, max) = (3.786, 3.857, 3.894), stdev = 0.062
  CI (99.9%): [2.726, 4.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 12.511 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.007 ms/op
Iteration   1: 3.723 ±(99.9%) 0.004 ms/op
Iteration   2: 3.725 ±(99.9%) 0.008 ms/op
Iteration   3: 3.739 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.729 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (3.723, 3.729, 3.739), stdev = 0.009
  CI (99.9%): [3.569, 3.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 12.257 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.706 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.007 ms/op
Iteration   1: 4.075 ±(99.9%) 0.004 ms/op
Iteration   2: 3.956 ±(99.9%) 0.004 ms/op
Iteration   3: 3.863 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.965 ±(99.9%) 1.933 ms/op [Average]
  (min, avg, max) = (3.863, 3.965, 4.075), stdev = 0.106
  CI (99.9%): [2.032, 5.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 13.560 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.298 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.764 ±(99.9%) 0.007 ms/op
Iteration   1: 4.584 ±(99.9%) 0.009 ms/op
Iteration   2: 4.479 ±(99.9%) 0.014 ms/op
Iteration   3: 4.579 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.547 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (4.479, 4.547, 4.584), stdev = 0.059
  CI (99.9%): [3.472, 5.622] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 13.552 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.347 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.017 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  22.761 ms/op
                 createUser·p0.9999: 25.686 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   2: 3.764 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   6.054 ms/op
                 createUser·p0.999:  25.231 ms/op
                 createUser·p0.9999: 29.819 ms/op
                 createUser·p1.00:   31.359 ms/op

Iteration   3: 3.910 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.477 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.560 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  23.298 ms/op
                 createUser·p0.9999: 39.506 ms/op
                 createUser·p1.00:   41.615 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 247210
  mean =      3.882 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236502 
    [ 5.000, 10.000) = 10033 
    [10.000, 15.000) = 294 
    [15.000, 20.000) = 93 
    [20.000, 25.000) = 111 
    [25.000, 30.000) = 141 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 29 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     38.470 ms/op
     p(99.9990) =     40.042 ms/op
     p(99.9999) =     41.615 ms/op
    p(100.0000) =     41.615 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.579 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.013 ms/op
Iteration   1: 3.703 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.800 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.116 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  23.626 ms/op
                 existUser·p0.9999: 25.997 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   2: 3.704 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.710 ms/op
                 existUser·p0.99:   6.611 ms/op
                 existUser·p0.999:  10.635 ms/op
                 existUser·p0.9999: 25.718 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.721 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.833 ms/op
                 existUser·p0.99:   6.595 ms/op
                 existUser·p0.999:  26.608 ms/op
                 existUser·p0.9999: 29.603 ms/op
                 existUser·p1.00:   29.983 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 258785
  mean =      3.709 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1344 
    [ 2.500,  5.000) = 247887 
    [ 5.000,  7.500) = 8064 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 81 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     16.372 ms/op
     p(99.9900) =     28.630 ms/op
     p(99.9990) =     29.780 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 12.655 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.014 ms/op
Iteration   1: 3.964 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   7.760 ms/op
                 getUser·p0.999:  16.286 ms/op
                 getUser·p0.9999: 23.851 ms/op
                 getUser·p1.00:   28.836 ms/op

Iteration   2: 3.702 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.378 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  22.158 ms/op
                 getUser·p0.9999: 24.469 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   3: 3.828 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.169 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   7.297 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 28.899 ms/op
                 getUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 250603
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 723 
    [ 2.500,  5.000) = 236926 
    [ 5.000,  7.500) = 10887 
    [ 7.500, 10.000) = 1485 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     27.155 ms/op
     p(99.9990) =     29.195 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.901 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.451 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.650 ±(99.9%) 0.017 ms/op
Iteration   1: 4.551 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.507 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  26.654 ms/op
                 listUser·p0.9999: 30.015 ms/op
                 listUser·p1.00:   31.228 ms/op

Iteration   2: 4.496 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.284 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.245 ms/op
                 listUser·p0.9999: 21.915 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.759 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   9.325 ms/op
                 listUser·p0.999:  17.066 ms/op
                 listUser·p0.9999: 19.319 ms/op
                 listUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208582
  mean =      4.599 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 178298 
    [ 5.000,  7.500) = 25341 
    [ 7.500, 10.000) = 3689 
    [10.000, 12.500) = 567 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     18.831 ms/op
     p(99.9900) =     29.201 ms/op
     p(99.9990) =     30.474 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.134 ± 4.382  ops/ms
ClientPb.existUser                       thrpt       3   8.297 ± 6.182  ops/ms
ClientPb.getUser                         thrpt       3   8.384 ± 4.710  ops/ms
ClientPb.listUser                        thrpt       3   6.912 ± 0.930  ops/ms
ClientPb.createUser                       avgt       3   3.857 ± 1.131   ms/op
ClientPb.existUser                        avgt       3   3.729 ± 0.160   ms/op
ClientPb.getUser                          avgt       3   3.965 ± 1.933   ms/op
ClientPb.listUser                         avgt       3   4.547 ± 1.075   ms/op
ClientPb.createUser                     sample  247210   3.882 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.348           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.734           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.265           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.470           ms/op
ClientPb.createUser:createUser·p1.00    sample          41.615           ms/op
ClientPb.existUser                      sample  258785   3.709 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.286           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.694           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.750           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.372           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.630           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.983           ms/op
ClientPb.getUser                        sample  250603   3.828 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.169           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.217           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.186           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.155           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  208582   4.599 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.028           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.831           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.201           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.228           ms/op
