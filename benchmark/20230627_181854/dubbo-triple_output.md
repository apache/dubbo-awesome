# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.653 ops/ms
# Warmup Iteration   2: 3.884 ops/ms
# Warmup Iteration   3: 7.674 ops/ms
Iteration   1: 7.993 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.174 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.084 ±(99.9%) 1.659 ops/ms [Average]
  (min, avg, max) = (7.993, 8.084, 8.174), stdev = 0.091
  CI (99.9%): [6.426, 9.743] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.461 ops/ms
# Warmup Iteration   2: 7.249 ops/ms
# Warmup Iteration   3: 8.326 ops/ms
Iteration   1: 8.589 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.452 ±(99.9%) 3.787 ops/ms [Average]
  (min, avg, max) = (8.213, 8.452, 8.589), stdev = 0.208
  CI (99.9%): [4.665, 12.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.335 ops/ms
# Warmup Iteration   2: 6.469 ops/ms
# Warmup Iteration   3: 7.972 ops/ms
Iteration   1: 8.306 ops/ms
Iteration   2: 8.265 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.309 ±(99.9%) 0.815 ops/ms [Average]
  (min, avg, max) = (8.265, 8.309, 8.354), stdev = 0.045
  CI (99.9%): [7.494, 9.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.099 ops/ms
# Warmup Iteration   2: 5.784 ops/ms
# Warmup Iteration   3: 6.692 ops/ms
Iteration   1: 6.684 ops/ms
Iteration   2: 6.854 ops/ms
Iteration   3: 7.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.852 ±(99.9%) 3.030 ops/ms [Average]
  (min, avg, max) = (6.684, 6.852, 7.017), stdev = 0.166
  CI (99.9%): [3.822, 9.881] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 13.866 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.006 ms/op
Iteration   1: 3.862 ±(99.9%) 0.005 ms/op
Iteration   2: 3.823 ±(99.9%) 0.014 ms/op
Iteration   3: 3.781 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.822 ±(99.9%) 0.744 ms/op [Average]
  (min, avg, max) = (3.781, 3.822, 3.862), stdev = 0.041
  CI (99.9%): [3.078, 4.566] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 14.130 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.007 ms/op
Iteration   1: 3.813 ±(99.9%) 0.010 ms/op
Iteration   2: 3.702 ±(99.9%) 0.006 ms/op
Iteration   3: 3.732 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.749 ±(99.9%) 1.049 ms/op [Average]
  (min, avg, max) = (3.702, 3.749, 3.813), stdev = 0.057
  CI (99.9%): [2.700, 4.798] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.047 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.008 ms/op
Iteration   1: 4.084 ±(99.9%) 0.008 ms/op
Iteration   2: 3.892 ±(99.9%) 0.010 ms/op
Iteration   3: 3.939 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.972 ±(99.9%) 1.823 ms/op [Average]
  (min, avg, max) = (3.892, 3.972, 4.084), stdev = 0.100
  CI (99.9%): [2.149, 5.794] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.261 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.010 ms/op
Iteration   1: 4.604 ±(99.9%) 0.012 ms/op
Iteration   2: 4.522 ±(99.9%) 0.016 ms/op
Iteration   3: 4.701 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.609 ±(99.9%) 1.630 ms/op [Average]
  (min, avg, max) = (4.522, 4.609, 4.701), stdev = 0.089
  CI (99.9%): [2.979, 6.239] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.243 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.294 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.016 ms/op
Iteration   1: 3.910 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.851 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   7.750 ms/op
                 createUser·p0.999:  23.366 ms/op
                 createUser·p0.9999: 26.077 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.952 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.974 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.585 ms/op
                 createUser·p0.999:  21.889 ms/op
                 createUser·p0.9999: 27.620 ms/op
                 createUser·p1.00:   30.736 ms/op

Iteration   3: 3.950 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.913 ms/op
                 createUser·p0.50:   3.834 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.832 ms/op
                 createUser·p0.999:  20.603 ms/op
                 createUser·p0.9999: 32.142 ms/op
                 createUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 243968
  mean =      3.937 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 302 
    [ 2.500,  5.000) = 233876 
    [ 5.000,  7.500) = 7669 
    [ 7.500, 10.000) = 1508 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.851 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     21.889 ms/op
     p(99.9900) =     31.412 ms/op
     p(99.9990) =     32.522 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.033 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.014 ms/op
Iteration   1: 3.826 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.225 ms/op
                 existUser·p0.999:  23.441 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.863 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   7.470 ms/op
                 existUser·p0.999:  15.565 ms/op
                 existUser·p0.9999: 26.946 ms/op
                 existUser·p1.00:   30.015 ms/op

Iteration   3: 3.762 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   6.324 ms/op
                 existUser·p0.999:  27.067 ms/op
                 existUser·p0.9999: 29.885 ms/op
                 existUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251412
  mean =      3.817 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 408 
    [ 2.500,  5.000) = 241373 
    [ 5.000,  7.500) = 7671 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 300 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 110 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     29.173 ms/op
     p(99.9990) =     32.555 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.938 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.715 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.015 ms/op
Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.079 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  14.527 ms/op
                 getUser·p0.9999: 25.924 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 3.948 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   5.005 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  24.738 ms/op
                 getUser·p0.9999: 32.571 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   3: 4.073 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.645 ms/op
                 getUser·p0.50:   3.850 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.947 ms/op
                 getUser·p0.99:   7.512 ms/op
                 getUser·p0.999:  12.927 ms/op
                 getUser·p0.9999: 44.368 ms/op
                 getUser·p1.00:   45.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238185
  mean =      4.029 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 222185 
    [ 5.000, 10.000) = 15401 
    [10.000, 15.000) = 361 
    [15.000, 20.000) = 14 
    [20.000, 25.000) = 64 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.595 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.462 ms/op
     p(99.0000) =      7.668 ms/op
     p(99.9000) =     15.062 ms/op
     p(99.9900) =     42.491 ms/op
     p(99.9990) =     45.004 ms/op
     p(99.9999) =     45.351 ms/op
    p(100.0000) =     45.351 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.087 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.265 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.752 ±(99.9%) 0.016 ms/op
Iteration   1: 4.613 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  24.337 ms/op
                 listUser·p0.9999: 27.368 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.547 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.241 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 20.705 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.560 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.646 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  16.071 ms/op
                 listUser·p0.9999: 21.233 ms/op
                 listUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209830
  mean =      4.573 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 187505 
    [ 5.000,  7.500) = 18224 
    [ 7.500, 10.000) = 2969 
    [10.000, 12.500) = 637 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     26.314 ms/op
     p(99.9990) =     28.237 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.084 ± 1.659  ops/ms
ClientPb.existUser                       thrpt       3   8.452 ± 3.787  ops/ms
ClientPb.getUser                         thrpt       3   8.309 ± 0.815  ops/ms
ClientPb.listUser                        thrpt       3   6.852 ± 3.030  ops/ms
ClientPb.createUser                       avgt       3   3.822 ± 0.744   ms/op
ClientPb.existUser                        avgt       3   3.749 ± 1.049   ms/op
ClientPb.getUser                          avgt       3   3.972 ± 1.823   ms/op
ClientPb.listUser                         avgt       3   4.609 ± 1.630   ms/op
ClientPb.createUser                     sample  243968   3.937 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.851           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.456           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.143           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.889           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.258           ms/op
ClientPb.existUser                      sample  251412   3.817 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.932           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.227           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.053           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.298           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.173           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.735           ms/op
ClientPb.getUser                        sample  238185   4.029 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.595           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.637           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.462           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.062           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.491           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.351           ms/op
ClientPb.listUser                       sample  209830   4.573 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.314           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
