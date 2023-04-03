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
# Warmup Iteration   1: 1.645 ops/ms
# Warmup Iteration   2: 3.505 ops/ms
# Warmup Iteration   3: 7.371 ops/ms
Iteration   1: 7.731 ops/ms
Iteration   2: 7.793 ops/ms
Iteration   3: 7.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.807 ±(99.9%) 1.525 ops/ms [Average]
  (min, avg, max) = (7.731, 7.807, 7.896), stdev = 0.084
  CI (99.9%): [6.282, 9.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.379 ops/ms
# Warmup Iteration   2: 6.594 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 8.549 ops/ms
Iteration   2: 8.599 ops/ms
Iteration   3: 8.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.447 ±(99.9%) 4.030 ops/ms [Average]
  (min, avg, max) = (8.194, 8.447, 8.599), stdev = 0.221
  CI (99.9%): [4.417, 12.477] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.341 ops/ms
# Warmup Iteration   2: 6.225 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 7.740 ops/ms
Iteration   2: 7.350 ops/ms
Iteration   3: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.677 ±(99.9%) 5.487 ops/ms [Average]
  (min, avg, max) = (7.350, 7.677, 7.942), stdev = 0.301
  CI (99.9%): [2.190, 13.164] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.133 ops/ms
# Warmup Iteration   3: 6.632 ops/ms
Iteration   1: 6.074 ops/ms
Iteration   2: 6.227 ops/ms
Iteration   3: 6.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.238 ±(99.9%) 3.102 ops/ms [Average]
  (min, avg, max) = (6.074, 6.238, 6.413), stdev = 0.170
  CI (99.9%): [3.135, 9.340] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.656 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 5.006 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.228 ±(99.9%) 0.007 ms/op
Iteration   1: 3.924 ±(99.9%) 0.009 ms/op
Iteration   2: 3.869 ±(99.9%) 0.007 ms/op
Iteration   3: 3.860 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.884 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (3.860, 3.884, 3.924), stdev = 0.035
  CI (99.9%): [3.243, 4.525] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.126 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.005 ms/op
Iteration   1: 3.738 ±(99.9%) 0.008 ms/op
Iteration   2: 3.716 ±(99.9%) 0.006 ms/op
Iteration   3: 3.790 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.748 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.716, 3.748, 3.790), stdev = 0.038
  CI (99.9%): [3.052, 4.444] (assumes normal distribution)


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
# Warmup Iteration   1: 11.679 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.005 ms/op
Iteration   1: 4.109 ±(99.9%) 0.006 ms/op
Iteration   2: 3.933 ±(99.9%) 0.010 ms/op
Iteration   3: 3.949 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.997 ±(99.9%) 1.777 ms/op [Average]
  (min, avg, max) = (3.933, 3.997, 4.109), stdev = 0.097
  CI (99.9%): [2.221, 5.774] (assumes normal distribution)


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
# Warmup Iteration   1: 14.594 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.373 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.746 ±(99.9%) 0.008 ms/op
Iteration   1: 4.604 ±(99.9%) 0.012 ms/op
Iteration   2: 4.536 ±(99.9%) 0.012 ms/op
Iteration   3: 4.679 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.606 ±(99.9%) 1.308 ms/op [Average]
  (min, avg, max) = (4.536, 4.606, 4.679), stdev = 0.072
  CI (99.9%): [3.299, 5.914] (assumes normal distribution)


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
# Warmup Iteration   1: 11.125 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.922 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.504 ±(99.9%) 0.019 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   2.030 ms/op
                 createUser·p0.50:   3.805 ms/op
                 createUser·p0.90:   4.882 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  11.477 ms/op
                 createUser·p0.9999: 24.677 ms/op
                 createUser·p1.00:   27.820 ms/op

Iteration   2: 3.892 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.375 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   7.015 ms/op
                 createUser·p0.999:  24.996 ms/op
                 createUser·p0.9999: 27.693 ms/op
                 createUser·p1.00:   29.164 ms/op

Iteration   3: 4.019 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  20.275 ms/op
                 createUser·p0.9999: 29.100 ms/op
                 createUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241464
  mean =      3.972 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 151 
    [ 2.500,  5.000) = 226862 
    [ 5.000,  7.500) = 12696 
    [ 7.500, 10.000) = 1212 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.801 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     20.089 ms/op
     p(99.9900) =     28.803 ms/op
     p(99.9990) =     30.377 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 11.760 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.011 ms/op
Iteration   1: 3.850 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   7.840 ms/op
                 existUser·p0.999:  12.320 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   27.296 ms/op

Iteration   2: 3.888 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.776 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  24.866 ms/op
                 existUser·p0.9999: 31.649 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   3: 3.820 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.823 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.092 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  12.468 ms/op
                 existUser·p0.9999: 29.020 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 248941
  mean =      3.852 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 200 
    [ 2.500,  5.000) = 238152 
    [ 5.000,  7.500) = 8701 
    [ 7.500, 10.000) = 1288 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     29.396 ms/op
     p(99.9990) =     32.260 ms/op
     p(99.9999) =     32.276 ms/op
    p(100.0000) =     32.276 ms/op


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
# Warmup Iteration   1: 13.316 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.689 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.015 ms/op
Iteration   1: 3.912 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.813 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.855 ms/op
                 getUser·p0.999:  23.602 ms/op
                 getUser·p0.9999: 25.979 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 3.922 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.993 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  10.297 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   3: 3.947 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.727 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.913 ms/op
                 getUser·p0.999:  28.639 ms/op
                 getUser·p0.9999: 33.154 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 244354
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 233275 
    [ 5.000,  7.500) = 8927 
    [ 7.500, 10.000) = 1406 
    [10.000, 12.500) = 327 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.458 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     23.450 ms/op
     p(99.9900) =     31.265 ms/op
     p(99.9990) =     33.671 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 14.875 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 5.180 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.834 ±(99.9%) 0.018 ms/op
Iteration   1: 4.615 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.640 ms/op
                 listUser·p0.50:   4.358 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   9.802 ms/op
                 listUser·p0.999:  23.313 ms/op
                 listUser·p0.9999: 25.103 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.567 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  16.694 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 4.505 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  16.631 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 210261
  mean =      4.562 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 191345 
    [ 5.000,  7.500) = 14736 
    [ 7.500, 10.000) = 3097 
    [10.000, 12.500) = 585 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     24.574 ms/op
     p(99.9990) =     25.588 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.807 ± 1.525  ops/ms
ClientPb.existUser                       thrpt       3   8.447 ± 4.030  ops/ms
ClientPb.getUser                         thrpt       3   7.677 ± 5.487  ops/ms
ClientPb.listUser                        thrpt       3   6.238 ± 3.102  ops/ms
ClientPb.createUser                       avgt       3   3.884 ± 0.641   ms/op
ClientPb.existUser                        avgt       3   3.748 ± 0.696   ms/op
ClientPb.getUser                          avgt       3   3.997 ± 1.777   ms/op
ClientPb.listUser                         avgt       3   4.606 ± 1.308   ms/op
ClientPb.createUser                     sample  241464   3.972 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.700           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.045           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.089           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.539           ms/op
ClientPb.existUser                      sample  248941   3.852 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.700           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.235           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.792           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.418           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.396           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.276           ms/op
ClientPb.getUser                        sample  244354   3.927 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.458           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.415           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.450           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.265           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  210261   4.562 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.640           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.390           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.574           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.575           ms/op
