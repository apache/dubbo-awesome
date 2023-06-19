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
# Warmup Iteration   1: 1.185 ops/ms
# Warmup Iteration   2: 3.040 ops/ms
# Warmup Iteration   3: 5.881 ops/ms
Iteration   1: 5.923 ops/ms
Iteration   2: 6.135 ops/ms
Iteration   3: 6.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.056 ±(99.9%) 2.119 ops/ms [Average]
  (min, avg, max) = (5.923, 6.056, 6.135), stdev = 0.116
  CI (99.9%): [3.938, 8.175] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.882 ops/ms
# Warmup Iteration   2: 5.643 ops/ms
# Warmup Iteration   3: 6.747 ops/ms
Iteration   1: 6.670 ops/ms
Iteration   2: 6.560 ops/ms
Iteration   3: 6.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.688 ±(99.9%) 2.511 ops/ms [Average]
  (min, avg, max) = (6.560, 6.688, 6.834), stdev = 0.138
  CI (99.9%): [4.177, 9.199] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 5.295 ops/ms
# Warmup Iteration   3: 6.193 ops/ms
Iteration   1: 6.202 ops/ms
Iteration   2: 6.217 ops/ms
Iteration   3: 6.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.283 ±(99.9%) 2.325 ops/ms [Average]
  (min, avg, max) = (6.202, 6.283, 6.430), stdev = 0.127
  CI (99.9%): [3.958, 8.608] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.753 ops/ms
# Warmup Iteration   2: 4.386 ops/ms
# Warmup Iteration   3: 5.188 ops/ms
Iteration   1: 5.230 ops/ms
Iteration   2: 5.312 ops/ms
Iteration   3: 5.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.306 ±(99.9%) 1.330 ops/ms [Average]
  (min, avg, max) = (5.230, 5.306, 5.375), stdev = 0.073
  CI (99.9%): [3.976, 6.636] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.297 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.203 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.388 ±(99.9%) 0.014 ms/op
Iteration   1: 5.243 ±(99.9%) 0.011 ms/op
Iteration   2: 5.193 ±(99.9%) 0.005 ms/op
Iteration   3: 5.007 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.148 ±(99.9%) 2.264 ms/op [Average]
  (min, avg, max) = (5.007, 5.148, 5.243), stdev = 0.124
  CI (99.9%): [2.884, 7.411] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.043 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.888 ±(99.9%) 0.011 ms/op
Iteration   1: 4.874 ±(99.9%) 0.013 ms/op
Iteration   2: 4.904 ±(99.9%) 0.012 ms/op
Iteration   3: 4.806 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.861 ±(99.9%) 0.915 ms/op [Average]
  (min, avg, max) = (4.806, 4.861, 4.904), stdev = 0.050
  CI (99.9%): [3.947, 5.776] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.565 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.069 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.075 ±(99.9%) 0.020 ms/op
Iteration   1: 5.177 ±(99.9%) 0.010 ms/op
Iteration   2: 5.212 ±(99.9%) 0.011 ms/op
Iteration   3: 4.929 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.106 ±(99.9%) 2.808 ms/op [Average]
  (min, avg, max) = (4.929, 5.106, 5.212), stdev = 0.154
  CI (99.9%): [2.298, 7.914] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.601 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.862 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.281 ±(99.9%) 0.011 ms/op
Iteration   1: 5.882 ±(99.9%) 0.018 ms/op
Iteration   2: 5.676 ±(99.9%) 0.019 ms/op
Iteration   3: 5.745 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.768 ±(99.9%) 1.913 ms/op [Average]
  (min, avg, max) = (5.676, 5.768, 5.882), stdev = 0.105
  CI (99.9%): [3.854, 7.681] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.053 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 6.309 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.570 ±(99.9%) 0.024 ms/op
Iteration   1: 5.211 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   4.923 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   10.240 ms/op
                 createUser·p0.999:  25.133 ms/op
                 createUser·p0.9999: 29.056 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   2: 4.961 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   4.727 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   6.709 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  22.581 ms/op
                 createUser·p0.9999: 32.415 ms/op
                 createUser·p1.00:   33.882 ms/op

Iteration   3: 5.094 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.241 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.242 ms/op
                 createUser·p0.95:   6.898 ms/op
                 createUser·p0.99:   9.257 ms/op
                 createUser·p0.999:  26.518 ms/op
                 createUser·p0.9999: 30.060 ms/op
                 createUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 188501
  mean =      5.086 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 112168 
    [ 5.000,  7.500) = 69866 
    [ 7.500, 10.000) = 4932 
    [10.000, 12.500) = 941 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.267 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     25.133 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     33.824 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.240 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 5.926 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.252 ±(99.9%) 0.020 ms/op
Iteration   1: 4.918 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.755 ms/op
                 existUser·p0.50:   4.637 ms/op
                 existUser·p0.90:   6.177 ms/op
                 existUser·p0.95:   6.988 ms/op
                 existUser·p0.99:   9.131 ms/op
                 existUser·p0.999:  13.722 ms/op
                 existUser·p0.9999: 27.017 ms/op
                 existUser·p1.00:   28.082 ms/op

Iteration   2: 4.773 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.046 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.644 ms/op
                 existUser·p0.95:   6.275 ms/op
                 existUser·p0.99:   9.126 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 30.073 ms/op
                 existUser·p1.00:   30.802 ms/op

Iteration   3: 4.884 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.935 ms/op
                 existUser·p0.50:   4.628 ms/op
                 existUser·p0.90:   6.013 ms/op
                 existUser·p0.95:   7.102 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  20.881 ms/op
                 existUser·p0.9999: 30.647 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197444
  mean =      4.857 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 140937 
    [ 5.000,  7.500) = 50232 
    [ 7.500, 10.000) = 4880 
    [10.000, 12.500) = 861 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.755 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.947 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     15.164 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     30.903 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.605 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.802 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.214 ±(99.9%) 0.021 ms/op
Iteration   1: 5.286 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.593 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.169 ms/op
                 getUser·p0.95:   7.774 ms/op
                 getUser·p0.99:   11.846 ms/op
                 getUser·p0.999:  24.722 ms/op
                 getUser·p0.9999: 28.142 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   2: 5.338 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.302 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.717 ms/op
                 getUser·p0.95:   8.290 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  25.693 ms/op
                 getUser·p0.9999: 29.459 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 5.084 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.281 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   7.094 ms/op
                 getUser·p0.99:   9.650 ms/op
                 getUser·p0.999:  27.113 ms/op
                 getUser·p0.9999: 30.760 ms/op
                 getUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 183348
  mean =      5.234 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 99088 
    [ 5.000,  7.500) = 73885 
    [ 7.500, 10.000) = 7658 
    [10.000, 12.500) = 1821 
    [12.500, 15.000) = 447 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 95 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.281 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      7.758 ms/op
     p(99.0000) =     10.830 ms/op
     p(99.9000) =     25.166 ms/op
     p(99.9900) =     29.994 ms/op
     p(99.9990) =     32.735 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 17.211 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 7.340 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.125 ±(99.9%) 0.025 ms/op
Iteration   1: 6.149 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.634 ms/op
                 listUser·p0.50:   5.833 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   12.288 ms/op
                 listUser·p0.999:  26.378 ms/op
                 listUser·p0.9999: 30.389 ms/op
                 listUser·p1.00:   31.064 ms/op

Iteration   2: 6.303 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   8.028 ms/op
                 listUser·p0.95:   9.339 ms/op
                 listUser·p0.99:   12.173 ms/op
                 listUser·p0.999:  28.002 ms/op
                 listUser·p0.9999: 31.015 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   3: 6.195 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.839 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.302 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   11.663 ms/op
                 listUser·p0.999:  22.754 ms/op
                 listUser·p0.9999: 26.537 ms/op
                 listUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154344
  mean =      6.215 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 11067 
    [ 5.000,  7.500) = 127792 
    [ 7.500, 10.000) = 11188 
    [10.000, 12.500) = 3038 
    [12.500, 15.000) = 813 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      5.874 ms/op
     p(90.0000) =      7.504 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     25.908 ms/op
     p(99.9900) =     30.296 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.056 ± 2.119  ops/ms
ClientPb.existUser                       thrpt       3   6.688 ± 2.511  ops/ms
ClientPb.getUser                         thrpt       3   6.283 ± 2.325  ops/ms
ClientPb.listUser                        thrpt       3   5.306 ± 1.330  ops/ms
ClientPb.createUser                       avgt       3   5.148 ± 2.264   ms/op
ClientPb.existUser                        avgt       3   4.861 ± 0.915   ms/op
ClientPb.getUser                          avgt       3   5.106 ± 2.808   ms/op
ClientPb.listUser                         avgt       3   5.768 ± 1.913   ms/op
ClientPb.createUser                     sample  188501   5.086 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.618           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.267           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.996           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.133           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.145           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  197444   4.857 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.755           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.604           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.840           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.306           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.164           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.819           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.999           ms/op
ClientPb.getUser                        sample  183348   5.234 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.281           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.758           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.830           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.166           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.994           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.193           ms/op
ClientPb.listUser                       sample  154344   6.215 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.393           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.874           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.504           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.831           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.026           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.908           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.296           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.047           ms/op
