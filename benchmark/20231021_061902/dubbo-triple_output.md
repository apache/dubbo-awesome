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
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 3.347 ops/ms
# Warmup Iteration   3: 6.758 ops/ms
Iteration   1: 7.014 ops/ms
Iteration   2: 7.800 ops/ms
Iteration   3: 7.703 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.506 ±(99.9%) 7.820 ops/ms [Average]
  (min, avg, max) = (7.014, 7.506, 7.800), stdev = 0.429
  CI (99.9%): [≈ 0, 15.325] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.914 ops/ms
# Warmup Iteration   2: 6.621 ops/ms
# Warmup Iteration   3: 7.952 ops/ms
Iteration   1: 7.828 ops/ms
Iteration   2: 8.243 ops/ms
Iteration   3: 7.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.978 ±(99.9%) 4.196 ops/ms [Average]
  (min, avg, max) = (7.828, 7.978, 8.243), stdev = 0.230
  CI (99.9%): [3.782, 12.174] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.994 ops/ms
# Warmup Iteration   2: 5.884 ops/ms
# Warmup Iteration   3: 7.677 ops/ms
Iteration   1: 7.499 ops/ms
Iteration   2: 7.946 ops/ms
Iteration   3: 7.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.788 ±(99.9%) 4.576 ops/ms [Average]
  (min, avg, max) = (7.499, 7.788, 7.946), stdev = 0.251
  CI (99.9%): [3.212, 12.364] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.937 ops/ms
# Warmup Iteration   2: 5.423 ops/ms
# Warmup Iteration   3: 6.500 ops/ms
Iteration   1: 6.384 ops/ms
Iteration   2: 6.550 ops/ms
Iteration   3: 6.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.507 ±(99.9%) 1.976 ops/ms [Average]
  (min, avg, max) = (6.384, 6.507, 6.587), stdev = 0.108
  CI (99.9%): [4.531, 8.482] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 13.095 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.462 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.407 ±(99.9%) 0.004 ms/op
Iteration   1: 4.260 ±(99.9%) 0.004 ms/op
Iteration   2: 4.080 ±(99.9%) 0.010 ms/op
Iteration   3: 4.217 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.186 ±(99.9%) 1.712 ms/op [Average]
  (min, avg, max) = (4.080, 4.186, 4.260), stdev = 0.094
  CI (99.9%): [2.474, 5.898] (assumes normal distribution)


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
# Warmup Iteration   1: 12.676 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.281 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.008 ms/op
Iteration   1: 3.899 ±(99.9%) 0.010 ms/op
Iteration   2: 4.055 ±(99.9%) 0.004 ms/op
Iteration   3: 3.869 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.941 ±(99.9%) 1.822 ms/op [Average]
  (min, avg, max) = (3.869, 3.941, 4.055), stdev = 0.100
  CI (99.9%): [2.119, 5.763] (assumes normal distribution)


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
# Warmup Iteration   1: 14.689 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.968 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.010 ms/op
Iteration   1: 4.041 ±(99.9%) 0.005 ms/op
Iteration   2: 4.077 ±(99.9%) 0.005 ms/op
Iteration   3: 4.218 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.112 ±(99.9%) 1.702 ms/op [Average]
  (min, avg, max) = (4.041, 4.112, 4.218), stdev = 0.093
  CI (99.9%): [2.410, 5.814] (assumes normal distribution)


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
# Warmup Iteration   1: 15.277 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.850 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.988 ±(99.9%) 0.005 ms/op
Iteration   1: 4.768 ±(99.9%) 0.008 ms/op
Iteration   2: 4.772 ±(99.9%) 0.008 ms/op
Iteration   3: 4.716 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.752 ±(99.9%) 0.565 ms/op [Average]
  (min, avg, max) = (4.716, 4.752, 4.772), stdev = 0.031
  CI (99.9%): [4.187, 5.318] (assumes normal distribution)


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
# Warmup Iteration   1: 13.358 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.133 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.533 ±(99.9%) 0.020 ms/op
Iteration   1: 4.051 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   7.442 ms/op
                 createUser·p0.999:  17.373 ms/op
                 createUser·p0.9999: 26.659 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   2: 4.117 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.987 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   7.642 ms/op
                 createUser·p0.999:  26.352 ms/op
                 createUser·p0.9999: 30.950 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   3: 4.096 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  18.544 ms/op
                 createUser·p0.9999: 29.209 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234779
  mean =      4.088 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 222928 
    [ 5.000,  7.500) = 9388 
    [ 7.500, 10.000) = 1386 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.495 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.397 ms/op
     p(99.9000) =     19.140 ms/op
     p(99.9900) =     29.461 ms/op
     p(99.9990) =     31.423 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


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
# Warmup Iteration   1: 13.506 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.513 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.011 ms/op
Iteration   1: 4.199 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.944 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.743 ms/op
                 existUser·p0.99:   8.651 ms/op
                 existUser·p0.999:  13.509 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 4.247 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.769 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  24.272 ms/op
                 existUser·p0.9999: 26.984 ms/op
                 existUser·p1.00:   28.279 ms/op

Iteration   3: 4.036 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.888 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   9.077 ms/op
                 existUser·p0.999:  14.528 ms/op
                 existUser·p0.9999: 33.817 ms/op
                 existUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 230735
  mean =      4.159 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 301 
    [ 2.500,  5.000) = 210962 
    [ 5.000,  7.500) = 14924 
    [ 7.500, 10.000) = 3217 
    [10.000, 12.500) = 968 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      8.815 ms/op
     p(99.9000) =     15.660 ms/op
     p(99.9900) =     32.241 ms/op
     p(99.9990) =     34.260 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 13.200 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.016 ms/op
Iteration   1: 4.084 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   8.253 ms/op
                 getUser·p0.999:  16.688 ms/op
                 getUser·p0.9999: 25.617 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.144 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.253 ms/op
                 getUser·p0.50:   3.932 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  12.292 ms/op
                 getUser·p0.9999: 24.773 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.957 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.351 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  25.175 ms/op
                 getUser·p0.9999: 28.836 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236626
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 220738 
    [ 5.000,  7.500) = 13258 
    [ 7.500, 10.000) = 1645 
    [10.000, 12.500) = 535 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 77 

  Percentiles, ms/op:
      p(0.0000) =      1.532 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     16.767 ms/op
     p(99.9900) =     27.973 ms/op
     p(99.9990) =     29.479 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 16.565 ±(99.9%) 0.256 ms/op
# Warmup Iteration   2: 5.953 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.079 ±(99.9%) 0.018 ms/op
Iteration   1: 5.050 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   9.617 ms/op
                 listUser·p0.999:  24.881 ms/op
                 listUser·p0.9999: 30.977 ms/op
                 listUser·p1.00:   31.654 ms/op

Iteration   2: 5.017 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   5.521 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  19.471 ms/op
                 listUser·p0.9999: 24.879 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.901 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 20.332 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192367
  mean =      4.989 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 127702 
    [ 5.000,  7.500) = 59173 
    [ 7.500, 10.000) = 4221 
    [10.000, 12.500) = 610 
    [12.500, 15.000) = 154 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     20.030 ms/op
     p(99.9900) =     29.026 ms/op
     p(99.9990) =     31.624 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.506 ± 7.820  ops/ms
ClientPb.existUser                       thrpt       3   7.978 ± 4.196  ops/ms
ClientPb.getUser                         thrpt       3   7.788 ± 4.576  ops/ms
ClientPb.listUser                        thrpt       3   6.507 ± 1.976  ops/ms
ClientPb.createUser                       avgt       3   4.186 ± 1.712   ms/op
ClientPb.existUser                        avgt       3   3.941 ± 1.822   ms/op
ClientPb.getUser                          avgt       3   4.112 ± 1.702   ms/op
ClientPb.listUser                         avgt       3   4.752 ± 0.565   ms/op
ClientPb.createUser                     sample  234779   4.088 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.495           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.397           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.140           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.461           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.490           ms/op
ClientPb.existUser                      sample  230735   4.159 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.358           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.949           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.866           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.815           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.660           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.241           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.652           ms/op
ClientPb.getUser                        sample  236626   4.060 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.532           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.627           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.767           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.973           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.655           ms/op
ClientPb.listUser                       sample  192367   4.989 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.232           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.776           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.267           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.030           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.026           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.654           ms/op
