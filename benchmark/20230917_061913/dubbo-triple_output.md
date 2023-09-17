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
# Warmup Iteration   1: 1.182 ops/ms
# Warmup Iteration   2: 2.362 ops/ms
# Warmup Iteration   3: 5.121 ops/ms
Iteration   1: 5.426 ops/ms
Iteration   2: 5.735 ops/ms
Iteration   3: 5.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.573 ±(99.9%) 2.826 ops/ms [Average]
  (min, avg, max) = (5.426, 5.573, 5.735), stdev = 0.155
  CI (99.9%): [2.748, 8.399] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.690 ops/ms
# Warmup Iteration   2: 4.594 ops/ms
# Warmup Iteration   3: 5.802 ops/ms
Iteration   1: 6.095 ops/ms
Iteration   2: 5.962 ops/ms
Iteration   3: 6.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.057 ±(99.9%) 1.520 ops/ms [Average]
  (min, avg, max) = (5.962, 6.057, 6.115), stdev = 0.083
  CI (99.9%): [4.537, 7.578] (assumes normal distribution)


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
# Warmup Iteration   1: 1.782 ops/ms
# Warmup Iteration   2: 4.728 ops/ms
# Warmup Iteration   3: 5.630 ops/ms
Iteration   1: 5.743 ops/ms
Iteration   2: 5.716 ops/ms
Iteration   3: 5.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.798 ±(99.9%) 2.177 ops/ms [Average]
  (min, avg, max) = (5.716, 5.798, 5.935), stdev = 0.119
  CI (99.9%): [3.621, 7.975] (assumes normal distribution)


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
# Warmup Iteration   1: 1.598 ops/ms
# Warmup Iteration   2: 4.017 ops/ms
# Warmup Iteration   3: 4.789 ops/ms
Iteration   1: 4.488 ops/ms
Iteration   2: 4.723 ops/ms
Iteration   3: 4.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.648 ±(99.9%) 2.541 ops/ms [Average]
  (min, avg, max) = (4.488, 4.648, 4.734), stdev = 0.139
  CI (99.9%): [2.107, 7.189] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 20.907 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.927 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.284 ±(99.9%) 0.013 ms/op
Iteration   1: 6.059 ±(99.9%) 0.013 ms/op
Iteration   2: 5.832 ±(99.9%) 0.013 ms/op
Iteration   3: 6.101 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.997 ±(99.9%) 2.637 ms/op [Average]
  (min, avg, max) = (5.832, 5.997, 6.101), stdev = 0.145
  CI (99.9%): [3.360, 8.634] (assumes normal distribution)


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
# Warmup Iteration   1: 20.693 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 7.556 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.285 ±(99.9%) 0.013 ms/op
Iteration   1: 5.932 ±(99.9%) 0.006 ms/op
Iteration   2: 5.694 ±(99.9%) 0.008 ms/op
Iteration   3: 5.773 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.800 ±(99.9%) 2.210 ms/op [Average]
  (min, avg, max) = (5.694, 5.800, 5.932), stdev = 0.121
  CI (99.9%): [3.589, 8.010] (assumes normal distribution)


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
# Warmup Iteration   1: 19.507 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 7.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.218 ±(99.9%) 0.008 ms/op
Iteration   1: 5.921 ±(99.9%) 0.009 ms/op
Iteration   2: 6.107 ±(99.9%) 0.008 ms/op
Iteration   3: 5.881 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.970 ±(99.9%) 2.205 ms/op [Average]
  (min, avg, max) = (5.881, 5.970, 6.107), stdev = 0.121
  CI (99.9%): [3.764, 8.175] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.977 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 8.824 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 7.335 ±(99.9%) 0.008 ms/op
Iteration   1: 7.022 ±(99.9%) 0.012 ms/op
Iteration   2: 6.862 ±(99.9%) 0.015 ms/op
Iteration   3: 7.027 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.970 ±(99.9%) 1.720 ms/op [Average]
  (min, avg, max) = (6.862, 6.970, 7.027), stdev = 0.094
  CI (99.9%): [5.251, 8.690] (assumes normal distribution)


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
# Warmup Iteration   1: 19.901 ±(99.9%) 0.319 ms/op
# Warmup Iteration   2: 8.035 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 6.359 ±(99.9%) 0.033 ms/op
Iteration   1: 5.945 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.454 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.717 ms/op
                 createUser·p0.95:   8.667 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  14.231 ms/op
                 createUser·p0.9999: 30.724 ms/op
                 createUser·p1.00:   31.687 ms/op

Iteration   2: 5.997 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.433 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.627 ms/op
                 createUser·p0.95:   8.684 ms/op
                 createUser·p0.99:   11.878 ms/op
                 createUser·p0.999:  31.701 ms/op
                 createUser·p0.9999: 39.082 ms/op
                 createUser·p1.00:   40.042 ms/op

Iteration   3: 5.924 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.126 ms/op
                 createUser·p0.50:   5.595 ms/op
                 createUser·p0.90:   7.373 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.370 ms/op
                 createUser·p0.999:  30.771 ms/op
                 createUser·p0.9999: 36.688 ms/op
                 createUser·p1.00:   37.028 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 161055
  mean =      5.955 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 36103 
    [ 5.000, 10.000) = 121450 
    [10.000, 15.000) = 3154 
    [15.000, 20.000) = 159 
    [20.000, 25.000) = 16 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 82 
    [35.000, 40.000) = 56 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.126 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.586 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     11.387 ms/op
     p(99.9000) =     28.761 ms/op
     p(99.9900) =     38.339 ms/op
     p(99.9990) =     39.642 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


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
# Warmup Iteration   1: 18.179 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 6.580 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.847 ±(99.9%) 0.024 ms/op
Iteration   1: 5.653 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.523 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.651 ms/op
                 existUser·p0.99:   11.682 ms/op
                 existUser·p0.999:  17.722 ms/op
                 existUser·p0.9999: 27.241 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   2: 5.811 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   5.382 ms/op
                 existUser·p0.90:   7.487 ms/op
                 existUser·p0.95:   8.816 ms/op
                 existUser·p0.99:   12.534 ms/op
                 existUser·p0.999:  22.706 ms/op
                 existUser·p0.9999: 26.115 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 6.000 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   5.505 ms/op
                 existUser·p0.90:   8.045 ms/op
                 existUser·p0.95:   9.388 ms/op
                 existUser·p0.99:   13.238 ms/op
                 existUser·p0.999:  23.587 ms/op
                 existUser·p0.9999: 26.478 ms/op
                 existUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 164931
  mean =      5.818 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 50785 
    [ 5.000,  7.500) = 96787 
    [ 7.500, 10.000) = 12718 
    [10.000, 12.500) = 3008 
    [12.500, 15.000) = 1025 
    [15.000, 17.500) = 320 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      5.358 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      8.995 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     20.289 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     30.240 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 18.272 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 7.568 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 5.988 ±(99.9%) 0.028 ms/op
Iteration   1: 5.964 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.970 ms/op
                 getUser·p0.50:   5.480 ms/op
                 getUser·p0.90:   7.610 ms/op
                 getUser·p0.95:   9.339 ms/op
                 getUser·p0.99:   13.490 ms/op
                 getUser·p0.999:  24.664 ms/op
                 getUser·p0.9999: 33.834 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   2: 5.758 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.507 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.086 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  27.886 ms/op
                 getUser·p0.9999: 32.604 ms/op
                 getUser·p1.00:   33.686 ms/op

Iteration   3: 6.030 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.122 ms/op
                 getUser·p0.50:   5.636 ms/op
                 getUser·p0.90:   7.741 ms/op
                 getUser·p0.95:   8.897 ms/op
                 getUser·p0.99:   12.059 ms/op
                 getUser·p0.999:  30.341 ms/op
                 getUser·p0.9999: 34.406 ms/op
                 getUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 162270
  mean =      5.915 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 38433 
    [ 5.000,  7.500) = 108003 
    [ 7.500, 10.000) = 11385 
    [10.000, 12.500) = 2847 
    [12.500, 15.000) = 762 
    [15.000, 17.500) = 381 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.970 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     12.435 ms/op
     p(99.9000) =     27.909 ms/op
     p(99.9900) =     33.736 ms/op
     p(99.9990) =     35.267 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 20.632 ±(99.9%) 0.393 ms/op
# Warmup Iteration   2: 8.540 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 7.205 ±(99.9%) 0.032 ms/op
Iteration   1: 7.225 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   3.400 ms/op
                 listUser·p0.50:   6.734 ms/op
                 listUser·p0.90:   9.355 ms/op
                 listUser·p0.95:   10.912 ms/op
                 listUser·p0.99:   15.155 ms/op
                 listUser·p0.999:  28.000 ms/op
                 listUser·p0.9999: 29.848 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   2: 7.125 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   3.248 ms/op
                 listUser·p0.50:   6.611 ms/op
                 listUser·p0.90:   8.880 ms/op
                 listUser·p0.95:   10.453 ms/op
                 listUser·p0.99:   15.207 ms/op
                 listUser·p0.999:  32.394 ms/op
                 listUser·p0.9999: 40.215 ms/op
                 listUser·p1.00:   41.943 ms/op

Iteration   3: 6.839 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   6.373 ms/op
                 listUser·p0.90:   8.536 ms/op
                 listUser·p0.95:   9.765 ms/op
                 listUser·p0.99:   13.460 ms/op
                 listUser·p0.999:  33.407 ms/op
                 listUser·p0.9999: 36.939 ms/op
                 listUser·p1.00:   37.224 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 135876
  mean =      7.059 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2389 
    [ 5.000, 10.000) = 125411 
    [10.000, 15.000) = 6847 
    [15.000, 20.000) = 873 
    [20.000, 25.000) = 54 
    [25.000, 30.000) = 154 
    [30.000, 35.000) = 92 
    [35.000, 40.000) = 52 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.245 ms/op
     p(50.0000) =      6.562 ms/op
     p(90.0000) =      8.913 ms/op
     p(95.0000) =     10.420 ms/op
     p(99.0000) =     14.696 ms/op
     p(99.9000) =     30.559 ms/op
     p(99.9900) =     38.354 ms/op
     p(99.9990) =     41.849 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.573 ± 2.826  ops/ms
ClientPb.existUser                       thrpt       3   6.057 ± 1.520  ops/ms
ClientPb.getUser                         thrpt       3   5.798 ± 2.177  ops/ms
ClientPb.listUser                        thrpt       3   4.648 ± 2.541  ops/ms
ClientPb.createUser                       avgt       3   5.997 ± 2.637   ms/op
ClientPb.existUser                        avgt       3   5.800 ± 2.210   ms/op
ClientPb.getUser                          avgt       3   5.970 ± 2.205   ms/op
ClientPb.listUser                         avgt       3   6.970 ± 1.720   ms/op
ClientPb.createUser                     sample  161055   5.955 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.126           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.586           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.585           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.387           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.339           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.042           ms/op
ClientPb.existUser                      sample  164931   5.818 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.154           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.594           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.995           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.452           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.289           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.378           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  162270   5.915 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.970           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.505           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.798           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.435           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.909           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.736           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  135876   7.059 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.562           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.420           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.696           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.559           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.943           ms/op
