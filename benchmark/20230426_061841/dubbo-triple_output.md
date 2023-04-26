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
# Warmup Iteration   1: 1.363 ops/ms
# Warmup Iteration   2: 3.107 ops/ms
# Warmup Iteration   3: 6.186 ops/ms
Iteration   1: 6.251 ops/ms
Iteration   2: 6.472 ops/ms
Iteration   3: 6.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.484 ±(99.9%) 4.379 ops/ms [Average]
  (min, avg, max) = (6.251, 6.484, 6.730), stdev = 0.240
  CI (99.9%): [2.106, 10.863] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.920 ops/ms
# Warmup Iteration   2: 5.932 ops/ms
# Warmup Iteration   3: 6.736 ops/ms
Iteration   1: 6.865 ops/ms
Iteration   2: 6.670 ops/ms
Iteration   3: 7.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.873 ±(99.9%) 3.772 ops/ms [Average]
  (min, avg, max) = (6.670, 6.873, 7.083), stdev = 0.207
  CI (99.9%): [3.100, 10.645] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.226 ops/ms
# Warmup Iteration   2: 6.173 ops/ms
# Warmup Iteration   3: 6.399 ops/ms
Iteration   1: 6.560 ops/ms
Iteration   2: 6.894 ops/ms
Iteration   3: 6.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.754 ±(99.9%) 3.169 ops/ms [Average]
  (min, avg, max) = (6.560, 6.754, 6.894), stdev = 0.174
  CI (99.9%): [3.586, 9.923] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.932 ops/ms
# Warmup Iteration   2: 5.096 ops/ms
# Warmup Iteration   3: 5.513 ops/ms
Iteration   1: 5.695 ops/ms
Iteration   2: 5.535 ops/ms
Iteration   3: 5.956 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.729 ±(99.9%) 3.882 ops/ms [Average]
  (min, avg, max) = (5.535, 5.729, 5.956), stdev = 0.213
  CI (99.9%): [1.846, 9.611] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.555 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.365 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.078 ±(99.9%) 0.019 ms/op
Iteration   1: 4.917 ±(99.9%) 0.012 ms/op
Iteration   2: 4.843 ±(99.9%) 0.019 ms/op
Iteration   3: 5.191 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.984 ±(99.9%) 3.349 ms/op [Average]
  (min, avg, max) = (4.843, 4.984, 5.191), stdev = 0.184
  CI (99.9%): [1.634, 8.333] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.394 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.121 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.009 ms/op
Iteration   1: 4.521 ±(99.9%) 0.011 ms/op
Iteration   2: 4.628 ±(99.9%) 0.009 ms/op
Iteration   3: 4.525 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.558 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (4.521, 4.558, 4.628), stdev = 0.061
  CI (99.9%): [3.453, 5.663] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.427 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.997 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.070 ±(99.9%) 0.014 ms/op
Iteration   1: 5.101 ±(99.9%) 0.009 ms/op
Iteration   2: 5.116 ±(99.9%) 0.012 ms/op
Iteration   3: 4.826 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.014 ±(99.9%) 2.982 ms/op [Average]
  (min, avg, max) = (4.826, 5.014, 5.116), stdev = 0.163
  CI (99.9%): [2.032, 7.996] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.235 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 6.224 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.576 ±(99.9%) 0.012 ms/op
Iteration   1: 5.629 ±(99.9%) 0.013 ms/op
Iteration   2: 5.584 ±(99.9%) 0.012 ms/op
Iteration   3: 5.522 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.578 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (5.522, 5.578, 5.629), stdev = 0.054
  CI (99.9%): [4.598, 6.559] (assumes normal distribution)


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
# Warmup Iteration   1: 14.972 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 6.020 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.341 ±(99.9%) 0.023 ms/op
Iteration   1: 4.742 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.865 ms/op
                 createUser·p0.95:   6.578 ms/op
                 createUser·p0.99:   9.339 ms/op
                 createUser·p0.999:  15.329 ms/op
                 createUser·p0.9999: 24.314 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 4.845 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   4.612 ms/op
                 createUser·p0.90:   5.997 ms/op
                 createUser·p0.95:   6.586 ms/op
                 createUser·p0.99:   8.348 ms/op
                 createUser·p0.999:  19.960 ms/op
                 createUser·p0.9999: 29.898 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 4.950 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.637 ms/op
                 createUser·p0.90:   6.128 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   10.441 ms/op
                 createUser·p0.999:  24.302 ms/op
                 createUser·p0.9999: 28.001 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 198032
  mean =      4.844 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 135346 
    [ 5.000,  7.500) = 57144 
    [ 7.500, 10.000) = 4052 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      5.997 ms/op
     p(95.0000) =      6.701 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     22.512 ms/op
     p(99.9900) =     28.154 ms/op
     p(99.9990) =     30.409 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 11.712 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.129 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.824 ±(99.9%) 0.016 ms/op
Iteration   1: 4.806 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.962 ms/op
                 existUser·p0.50:   4.563 ms/op
                 existUser·p0.90:   5.972 ms/op
                 existUser·p0.95:   7.053 ms/op
                 existUser·p0.99:   9.011 ms/op
                 existUser·p0.999:  16.211 ms/op
                 existUser·p0.9999: 25.265 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   2: 4.762 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   4.522 ms/op
                 existUser·p0.90:   5.775 ms/op
                 existUser·p0.95:   6.570 ms/op
                 existUser·p0.99:   9.241 ms/op
                 existUser·p0.999:  18.677 ms/op
                 existUser·p0.9999: 30.048 ms/op
                 existUser·p1.00:   30.704 ms/op

Iteration   3: 4.745 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.911 ms/op
                 existUser·p0.50:   4.514 ms/op
                 existUser·p0.90:   5.841 ms/op
                 existUser·p0.95:   6.595 ms/op
                 existUser·p0.99:   8.503 ms/op
                 existUser·p0.999:  17.630 ms/op
                 existUser·p0.9999: 27.739 ms/op
                 existUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 200973
  mean =      4.771 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 113 
    [ 2.500,  5.000) = 144615 
    [ 5.000,  7.500) = 50882 
    [ 7.500, 10.000) = 4045 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      6.734 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     28.512 ms/op
     p(99.9990) =     30.473 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 14.491 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.360 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.016 ms/op
Iteration   1: 5.053 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   6.439 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   11.593 ms/op
                 getUser·p0.999:  18.219 ms/op
                 getUser·p0.9999: 24.869 ms/op
                 getUser·p1.00:   26.083 ms/op

Iteration   2: 4.956 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.833 ms/op
                 getUser·p0.50:   4.719 ms/op
                 getUser·p0.90:   6.177 ms/op
                 getUser·p0.95:   6.791 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  18.186 ms/op
                 getUser·p0.9999: 26.075 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 4.989 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.372 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   6.136 ms/op
                 getUser·p0.95:   6.906 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  19.312 ms/op
                 getUser·p0.9999: 24.356 ms/op
                 getUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 191983
  mean =      4.999 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 120150 
    [ 5.000,  7.500) = 64577 
    [ 7.500, 10.000) = 5110 
    [10.000, 12.500) = 1328 
    [12.500, 15.000) = 431 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.242 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     25.553 ms/op
     p(99.9990) =     26.355 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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
# Warmup Iteration   1: 16.657 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.267 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.751 ±(99.9%) 0.019 ms/op
Iteration   1: 5.939 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   7.274 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   12.020 ms/op
                 listUser·p0.999:  23.467 ms/op
                 listUser·p0.9999: 27.787 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 5.673 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.864 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.348 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  21.168 ms/op
                 listUser·p0.9999: 25.199 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 5.901 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.058 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.258 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  20.646 ms/op
                 listUser·p0.9999: 25.517 ms/op
                 listUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164496
  mean =      5.835 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 35504 
    [ 5.000,  7.500) = 117228 
    [ 7.500, 10.000) = 8568 
    [10.000, 12.500) = 2056 
    [12.500, 15.000) = 630 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.864 ms/op
     p(50.0000) =      5.554 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.167 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     21.742 ms/op
     p(99.9900) =     26.167 ms/op
     p(99.9990) =     28.017 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.484 ± 4.379  ops/ms
ClientPb.existUser                       thrpt       3   6.873 ± 3.772  ops/ms
ClientPb.getUser                         thrpt       3   6.754 ± 3.169  ops/ms
ClientPb.listUser                        thrpt       3   5.729 ± 3.882  ops/ms
ClientPb.createUser                       avgt       3   4.984 ± 3.349   ms/op
ClientPb.existUser                        avgt       3   4.558 ± 1.105   ms/op
ClientPb.getUser                          avgt       3   5.014 ± 2.982   ms/op
ClientPb.listUser                         avgt       3   5.578 ± 0.980   ms/op
ClientPb.createUser                     sample  198032   4.844 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.182           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.997           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.701           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.355           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.512           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.154           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  200973   4.771 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.911           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.865           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.734           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.880           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.416           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.704           ms/op
ClientPb.getUser                        sample  191983   4.999 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.733           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.710           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.029           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.174           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.219           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.553           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.837           ms/op
ClientPb.listUser                       sample  164496   5.835 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.864           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.167           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.518           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.742           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.167           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
