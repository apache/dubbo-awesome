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
# Warmup Iteration   1: 1.581 ops/ms
# Warmup Iteration   2: 3.965 ops/ms
# Warmup Iteration   3: 7.508 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 7.783 ops/ms
Iteration   3: 7.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.835 ±(99.9%) 1.998 ops/ms [Average]
  (min, avg, max) = (7.761, 7.835, 7.961), stdev = 0.110
  CI (99.9%): [5.837, 9.833] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.143 ops/ms
# Warmup Iteration   2: 6.764 ops/ms
# Warmup Iteration   3: 8.571 ops/ms
Iteration   1: 8.198 ops/ms
Iteration   2: 8.424 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.410 ±(99.9%) 3.745 ops/ms [Average]
  (min, avg, max) = (8.198, 8.410, 8.608), stdev = 0.205
  CI (99.9%): [4.665, 12.154] (assumes normal distribution)


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
# Warmup Iteration   1: 2.235 ops/ms
# Warmup Iteration   2: 6.295 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 7.867 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.111 ±(99.9%) 3.862 ops/ms [Average]
  (min, avg, max) = (7.867, 8.111, 8.245), stdev = 0.212
  CI (99.9%): [4.249, 11.973] (assumes normal distribution)


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
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 4.966 ops/ms
# Warmup Iteration   3: 7.012 ops/ms
Iteration   1: 6.852 ops/ms
Iteration   2: 7.199 ops/ms
Iteration   3: 7.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.019 ±(99.9%) 3.171 ops/ms [Average]
  (min, avg, max) = (6.852, 7.019, 7.199), stdev = 0.174
  CI (99.9%): [3.848, 10.190] (assumes normal distribution)


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
# Warmup Iteration   1: 12.255 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.007 ms/op
Iteration   1: 3.888 ±(99.9%) 0.006 ms/op
Iteration   2: 3.953 ±(99.9%) 0.005 ms/op
Iteration   3: 3.759 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.867 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (3.759, 3.867, 3.953), stdev = 0.099
  CI (99.9%): [2.061, 5.672] (assumes normal distribution)


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
# Warmup Iteration   1: 13.072 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.012 ms/op
Iteration   1: 3.868 ±(99.9%) 0.007 ms/op
Iteration   2: 3.860 ±(99.9%) 0.007 ms/op
Iteration   3: 3.695 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.808 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.695, 3.808, 3.868), stdev = 0.097
  CI (99.9%): [2.032, 5.584] (assumes normal distribution)


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
# Warmup Iteration   1: 12.331 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.132 ±(99.9%) 0.005 ms/op
Iteration   1: 3.997 ±(99.9%) 0.008 ms/op
Iteration   2: 3.972 ±(99.9%) 0.013 ms/op
Iteration   3: 3.905 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.958 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.905, 3.958, 3.997), stdev = 0.047
  CI (99.9%): [3.096, 4.820] (assumes normal distribution)


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
# Warmup Iteration   1: 14.477 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.650 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.734 ±(99.9%) 0.007 ms/op
Iteration   1: 4.532 ±(99.9%) 0.012 ms/op
Iteration   2: 4.507 ±(99.9%) 0.015 ms/op
Iteration   3: 4.826 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.622 ±(99.9%) 3.237 ms/op [Average]
  (min, avg, max) = (4.507, 4.622, 4.826), stdev = 0.177
  CI (99.9%): [1.385, 7.858] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.992 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 5.146 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.018 ms/op
Iteration   1: 4.024 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.860 ms/op
                 createUser·p0.999:  22.169 ms/op
                 createUser·p0.9999: 24.286 ms/op
                 createUser·p1.00:   25.100 ms/op

Iteration   2: 4.351 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   5.546 ms/op
                 createUser·p0.95:   8.135 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  18.694 ms/op
                 createUser·p0.9999: 32.997 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   3: 3.795 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.999 ms/op
                 createUser·p0.50:   3.826 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  27.361 ms/op
                 createUser·p0.9999: 32.092 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237209
  mean =      4.044 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 544 
    [ 2.500,  5.000) = 221409 
    [ 5.000,  7.500) = 9983 
    [ 7.500, 10.000) = 4106 
    [10.000, 12.500) = 737 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.325 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     23.088 ms/op
     p(99.9900) =     32.248 ms/op
     p(99.9990) =     33.736 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 12.291 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.011 ms/op
Iteration   1: 3.759 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  23.429 ms/op
                 existUser·p0.9999: 26.328 ms/op
                 existUser·p1.00:   27.329 ms/op

Iteration   2: 3.954 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.400 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.628 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.168 ms/op
                 existUser·p0.999:  11.863 ms/op
                 existUser·p0.9999: 29.175 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.563 ms/op
                 existUser·p0.95:   5.358 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  13.144 ms/op
                 existUser·p0.9999: 29.685 ms/op
                 existUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246790
  mean =      3.889 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 265 
    [ 2.500,  5.000) = 234482 
    [ 5.000,  7.500) = 10524 
    [ 7.500, 10.000) = 1098 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     12.981 ms/op
     p(99.9900) =     29.085 ms/op
     p(99.9990) =     30.400 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 14.012 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.550 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
Iteration   1: 4.112 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.318 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.784 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  16.908 ms/op
                 getUser·p0.9999: 23.352 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.918 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.954 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  22.653 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.923 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.228 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  16.155 ms/op
                 getUser·p0.9999: 25.910 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240967
  mean =      3.982 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 230617 
    [ 5.000,  7.500) = 7813 
    [ 7.500, 10.000) = 1833 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     26.640 ms/op
     p(99.9990) =     28.012 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 14.884 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.304 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.017 ms/op
Iteration   1: 4.531 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.741 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   9.256 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 26.509 ms/op
                 listUser·p1.00:   27.296 ms/op

Iteration   2: 4.520 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  20.391 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   24.707 ms/op

Iteration   3: 4.714 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 21.772 ms/op
                 listUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209275
  mean =      4.587 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 186916 
    [ 5.000,  7.500) = 18325 
    [ 7.500, 10.000) = 2758 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 93 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.741 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     25.234 ms/op
     p(99.9990) =     27.030 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.835 ± 1.998  ops/ms
ClientPb.existUser                       thrpt       3   8.410 ± 3.745  ops/ms
ClientPb.getUser                         thrpt       3   8.111 ± 3.862  ops/ms
ClientPb.listUser                        thrpt       3   7.019 ± 3.171  ops/ms
ClientPb.createUser                       avgt       3   3.867 ± 1.806   ms/op
ClientPb.existUser                        avgt       3   3.808 ± 1.776   ms/op
ClientPb.getUser                          avgt       3   3.958 ± 0.862   ms/op
ClientPb.listUser                         avgt       3   4.622 ± 3.237   ms/op
ClientPb.createUser                     sample  237209   4.044 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.897           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.088           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.248           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.013           ms/op
ClientPb.existUser                      sample  246790   3.889 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.400           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.973           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.824           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.981           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.085           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.671           ms/op
ClientPb.getUser                        sample  240967   3.982 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.954           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.432           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.528           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.640           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  209275   4.587 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.741           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.299           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.234           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.296           ms/op
