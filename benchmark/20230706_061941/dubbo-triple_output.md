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
# Warmup Iteration   1: 1.627 ops/ms
# Warmup Iteration   2: 4.072 ops/ms
# Warmup Iteration   3: 7.128 ops/ms
Iteration   1: 7.907 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.146 ±(99.9%) 4.432 ops/ms [Average]
  (min, avg, max) = (7.907, 8.146, 8.393), stdev = 0.243
  CI (99.9%): [3.715, 12.578] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 6.615 ops/ms
# Warmup Iteration   3: 8.249 ops/ms
Iteration   1: 8.487 ops/ms
Iteration   2: 8.669 ops/ms
Iteration   3: 8.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.649 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (8.487, 8.649, 8.789), stdev = 0.152
  CI (99.9%): [5.872, 11.425] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.100 ops/ms
# Warmup Iteration   2: 6.391 ops/ms
# Warmup Iteration   3: 7.581 ops/ms
Iteration   1: 8.234 ops/ms
Iteration   2: 8.332 ops/ms
Iteration   3: 8.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.252 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (8.191, 8.252, 8.332), stdev = 0.072
  CI (99.9%): [6.931, 9.574] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.049 ops/ms
# Warmup Iteration   2: 5.565 ops/ms
# Warmup Iteration   3: 6.340 ops/ms
Iteration   1: 6.844 ops/ms
Iteration   2: 6.830 ops/ms
Iteration   3: 6.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.814 ±(99.9%) 0.757 ops/ms [Average]
  (min, avg, max) = (6.767, 6.814, 6.844), stdev = 0.041
  CI (99.9%): [6.057, 7.570] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.727 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.007 ms/op
Iteration   1: 3.903 ±(99.9%) 0.007 ms/op
Iteration   2: 3.882 ±(99.9%) 0.009 ms/op
Iteration   3: 3.833 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.873 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.833, 3.873, 3.903), stdev = 0.036
  CI (99.9%): [3.212, 4.534] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.131 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.004 ms/op
Iteration   1: 3.883 ±(99.9%) 0.007 ms/op
Iteration   2: 3.739 ±(99.9%) 0.005 ms/op
Iteration   3: 3.775 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.799 ±(99.9%) 1.364 ms/op [Average]
  (min, avg, max) = (3.739, 3.799, 3.883), stdev = 0.075
  CI (99.9%): [2.435, 5.163] (assumes normal distribution)


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
# Warmup Iteration   1: 12.634 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.125 ±(99.9%) 0.007 ms/op
Iteration   1: 3.974 ±(99.9%) 0.005 ms/op
Iteration   2: 4.040 ±(99.9%) 0.005 ms/op
Iteration   3: 4.081 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.031 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.974, 4.031, 4.081), stdev = 0.054
  CI (99.9%): [3.047, 5.016] (assumes normal distribution)


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
# Warmup Iteration   1: 14.335 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.901 ±(99.9%) 0.009 ms/op
Iteration   1: 4.933 ±(99.9%) 0.006 ms/op
Iteration   2: 4.827 ±(99.9%) 0.008 ms/op
Iteration   3: 4.606 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.789 ±(99.9%) 3.039 ms/op [Average]
  (min, avg, max) = (4.606, 4.789, 4.933), stdev = 0.167
  CI (99.9%): [1.749, 7.828] (assumes normal distribution)


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
# Warmup Iteration   1: 14.125 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 4.906 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.563 ±(99.9%) 0.020 ms/op
Iteration   1: 4.181 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  19.708 ms/op
                 createUser·p0.9999: 27.121 ms/op
                 createUser·p1.00:   28.344 ms/op

Iteration   2: 4.107 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.507 ms/op
                 createUser·p0.50:   3.891 ms/op
                 createUser·p0.90:   4.907 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  25.330 ms/op
                 createUser·p0.9999: 28.108 ms/op
                 createUser·p1.00:   29.590 ms/op

Iteration   3: 4.002 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.843 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  22.381 ms/op
                 createUser·p0.9999: 32.702 ms/op
                 createUser·p1.00:   32.932 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234474
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 268 
    [ 2.500,  5.000) = 216434 
    [ 5.000,  7.500) = 15743 
    [ 7.500, 10.000) = 1308 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 102 
    [27.500, 30.000) = 63 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     22.398 ms/op
     p(99.9900) =     31.071 ms/op
     p(99.9990) =     32.888 ms/op
     p(99.9999) =     32.932 ms/op
    p(100.0000) =     32.932 ms/op


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
# Warmup Iteration   1: 11.098 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.912 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
Iteration   1: 3.921 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.970 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.932 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  23.386 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 3.906 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.425 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  13.240 ms/op
                 existUser·p0.9999: 29.861 ms/op
                 existUser·p1.00:   30.867 ms/op

Iteration   3: 3.848 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   7.321 ms/op
                 existUser·p0.999:  17.260 ms/op
                 existUser·p0.9999: 35.635 ms/op
                 existUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246697
  mean =      3.892 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 303 
    [ 2.500,  5.000) = 235547 
    [ 5.000,  7.500) = 8821 
    [ 7.500, 10.000) = 1243 
    [10.000, 12.500) = 328 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     35.918 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 13.559 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.015 ms/op
Iteration   1: 4.136 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   7.856 ms/op
                 getUser·p0.999:  17.859 ms/op
                 getUser·p0.9999: 39.405 ms/op
                 getUser·p1.00:   42.009 ms/op

Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.245 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   5.218 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   8.151 ms/op
                 getUser·p0.999:  11.993 ms/op
                 getUser·p0.9999: 25.383 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 4.042 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.817 ms/op
                 getUser·p0.95:   5.161 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  27.034 ms/op
                 getUser·p0.9999: 28.937 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234397
  mean =      4.092 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 212828 
    [ 5.000, 10.000) = 20792 
    [10.000, 15.000) = 516 
    [15.000, 20.000) = 37 
    [20.000, 25.000) = 76 
    [25.000, 30.000) = 115 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 28 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     36.504 ms/op
     p(99.9990) =     41.943 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


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
# Warmup Iteration   1: 13.892 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 5.364 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.739 ±(99.9%) 0.017 ms/op
Iteration   1: 4.737 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  25.867 ms/op
                 listUser·p0.9999: 40.091 ms/op
                 listUser·p1.00:   42.467 ms/op

Iteration   2: 4.666 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.777 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  17.245 ms/op
                 listUser·p0.9999: 20.386 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 4.759 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  16.999 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203336
  mean =      4.720 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 163868 
    [ 5.000, 10.000) = 38573 
    [10.000, 15.000) = 477 
    [15.000, 20.000) = 237 
    [20.000, 25.000) = 79 
    [25.000, 30.000) = 70 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.982 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     19.245 ms/op
     p(99.9900) =     39.125 ms/op
     p(99.9990) =     41.770 ms/op
     p(99.9999) =     42.467 ms/op
    p(100.0000) =     42.467 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.146 ± 4.432  ops/ms
ClientPb.existUser                       thrpt       3   8.649 ± 2.777  ops/ms
ClientPb.getUser                         thrpt       3   8.252 ± 1.321  ops/ms
ClientPb.listUser                        thrpt       3   6.814 ± 0.757  ops/ms
ClientPb.createUser                       avgt       3   3.873 ± 0.661   ms/op
ClientPb.existUser                        avgt       3   3.799 ± 1.364   ms/op
ClientPb.getUser                          avgt       3   4.031 ± 0.984   ms/op
ClientPb.listUser                         avgt       3   4.789 ± 3.039   ms/op
ClientPb.createUser                     sample  234474   4.095 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.507           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.398           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.071           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.932           ms/op
ClientPb.existUser                      sample  246697   3.892 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.425           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.772           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.209           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.022           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.144           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.979           ms/op
ClientPb.getUser                        sample  234397   4.092 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.654           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.619           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.504           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.009           ms/op
ClientPb.listUser                       sample  203336   4.720 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.982           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.103           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.245           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.125           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.467           ms/op
