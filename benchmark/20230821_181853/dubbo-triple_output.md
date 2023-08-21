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
# Warmup Iteration   1: 1.412 ops/ms
# Warmup Iteration   2: 3.107 ops/ms
# Warmup Iteration   3: 6.280 ops/ms
Iteration   1: 7.052 ops/ms
Iteration   2: 7.722 ops/ms
Iteration   3: 7.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.507 ±(99.9%) 7.181 ops/ms [Average]
  (min, avg, max) = (7.052, 7.507, 7.745), stdev = 0.394
  CI (99.9%): [0.325, 14.688] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.151 ops/ms
# Warmup Iteration   2: 6.966 ops/ms
# Warmup Iteration   3: 8.172 ops/ms
Iteration   1: 8.215 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 8.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.249 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (8.167, 8.249, 8.366), stdev = 0.104
  CI (99.9%): [6.353, 10.146] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 6.339 ops/ms
# Warmup Iteration   3: 7.607 ops/ms
Iteration   1: 7.243 ops/ms
Iteration   2: 7.365 ops/ms
Iteration   3: 7.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.518 ±(99.9%) 6.854 ops/ms [Average]
  (min, avg, max) = (7.243, 7.518, 7.946), stdev = 0.376
  CI (99.9%): [0.664, 14.372] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.831 ops/ms
# Warmup Iteration   2: 5.055 ops/ms
# Warmup Iteration   3: 6.297 ops/ms
Iteration   1: 6.238 ops/ms
Iteration   2: 6.518 ops/ms
Iteration   3: 6.417 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.391 ±(99.9%) 2.583 ops/ms [Average]
  (min, avg, max) = (6.238, 6.391, 6.518), stdev = 0.142
  CI (99.9%): [3.808, 8.975] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.317 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.171 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.468 ±(99.9%) 0.006 ms/op
Iteration   1: 4.302 ±(99.9%) 0.005 ms/op
Iteration   2: 4.175 ±(99.9%) 0.005 ms/op
Iteration   3: 4.122 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.200 ±(99.9%) 1.688 ms/op [Average]
  (min, avg, max) = (4.122, 4.200, 4.302), stdev = 0.093
  CI (99.9%): [2.511, 5.888] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 13.603 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.817 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.006 ms/op
Iteration   1: 4.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.817 ±(99.9%) 0.004 ms/op
Iteration   3: 3.923 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.929 ±(99.9%) 2.124 ms/op [Average]
  (min, avg, max) = (3.817, 3.929, 4.049), stdev = 0.116
  CI (99.9%): [1.805, 6.053] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 14.513 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.152 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.009 ms/op
Iteration   1: 4.306 ±(99.9%) 0.005 ms/op
Iteration   2: 4.208 ±(99.9%) 0.009 ms/op
Iteration   3: 3.942 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.152 ±(99.9%) 3.435 ms/op [Average]
  (min, avg, max) = (3.942, 4.152, 4.306), stdev = 0.188
  CI (99.9%): [0.717, 7.587] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 16.026 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.932 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.215 ±(99.9%) 0.006 ms/op
Iteration   1: 4.639 ±(99.9%) 0.010 ms/op
Iteration   2: 4.901 ±(99.9%) 0.007 ms/op
Iteration   3: 4.715 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.752 ±(99.9%) 2.462 ms/op [Average]
  (min, avg, max) = (4.639, 4.752, 4.901), stdev = 0.135
  CI (99.9%): [2.290, 7.213] (assumes normal distribution)


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
# Warmup Iteration   1: 14.454 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.532 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.518 ±(99.9%) 0.020 ms/op
Iteration   1: 4.293 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.177 ms/op
                 createUser·p0.95:   6.349 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  21.710 ms/op
                 createUser·p0.9999: 24.412 ms/op
                 createUser·p1.00:   25.199 ms/op

Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 26.084 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   3: 4.070 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   3.858 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   8.323 ms/op
                 createUser·p0.999:  25.719 ms/op
                 createUser·p0.9999: 34.210 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234636
  mean =      4.086 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 354 
    [ 2.500,  5.000) = 217970 
    [ 5.000,  7.500) = 12219 
    [ 7.500, 10.000) = 2586 
    [10.000, 12.500) = 926 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     21.770 ms/op
     p(99.9900) =     32.049 ms/op
     p(99.9990) =     34.996 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.406 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 4.488 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.014 ms/op
Iteration   1: 3.934 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  23.542 ms/op
                 existUser·p0.9999: 30.719 ms/op
                 existUser·p1.00:   32.244 ms/op

Iteration   2: 3.886 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.829 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.948 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  14.313 ms/op
                 existUser·p0.9999: 31.246 ms/op
                 existUser·p1.00:   32.670 ms/op

Iteration   3: 3.951 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   8.602 ms/op
                 existUser·p0.999:  24.776 ms/op
                 existUser·p0.9999: 27.984 ms/op
                 existUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244548
  mean =      3.924 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 358 
    [ 2.500,  5.000) = 229707 
    [ 5.000,  7.500) = 11094 
    [ 7.500, 10.000) = 2287 
    [10.000, 12.500) = 595 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 78 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.452 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     22.839 ms/op
     p(99.9900) =     30.278 ms/op
     p(99.9990) =     32.480 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.109 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.014 ms/op
Iteration   1: 4.220 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.058 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.940 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   9.847 ms/op
                 getUser·p0.999:  24.904 ms/op
                 getUser·p0.9999: 27.548 ms/op
                 getUser·p1.00:   31.949 ms/op

Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   5.235 ms/op
                 getUser·p0.99:   7.954 ms/op
                 getUser·p0.999:  11.968 ms/op
                 getUser·p0.9999: 28.415 ms/op
                 getUser·p1.00:   30.245 ms/op

Iteration   3: 3.957 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.036 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  27.663 ms/op
                 getUser·p0.9999: 31.782 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235124
  mean =      4.079 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 219689 
    [ 5.000,  7.500) = 11214 
    [ 7.500, 10.000) = 2933 
    [10.000, 12.500) = 814 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 113 
    [27.500, 30.000) = 89 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     30.179 ms/op
     p(99.9990) =     32.263 ms/op
     p(99.9999) =     32.408 ms/op
    p(100.0000) =     32.408 ms/op


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
# Warmup Iteration   1: 15.799 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.599 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.198 ±(99.9%) 0.021 ms/op
Iteration   1: 5.346 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   12.090 ms/op
                 listUser·p0.999:  25.270 ms/op
                 listUser·p0.9999: 28.607 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 4.913 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   10.027 ms/op
                 listUser·p0.999:  23.888 ms/op
                 listUser·p0.9999: 28.819 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   3: 4.789 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   9.149 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 20.325 ms/op
                 listUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 191676
  mean =      5.005 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 140156 
    [ 5.000,  7.500) = 41533 
    [ 7.500, 10.000) = 7836 
    [10.000, 12.500) = 1156 
    [12.500, 15.000) = 484 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 87 

  Percentiles, ms/op:
      p(0.0000) =      2.032 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      5.865 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     23.516 ms/op
     p(99.9900) =     28.290 ms/op
     p(99.9990) =     29.068 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.507 ± 7.181  ops/ms
ClientPb.existUser                       thrpt       3   8.249 ± 1.896  ops/ms
ClientPb.getUser                         thrpt       3   7.518 ± 6.854  ops/ms
ClientPb.listUser                        thrpt       3   6.391 ± 2.583  ops/ms
ClientPb.createUser                       avgt       3   4.200 ± 1.688   ms/op
ClientPb.existUser                        avgt       3   3.929 ± 2.124   ms/op
ClientPb.getUser                          avgt       3   4.152 ± 3.435   ms/op
ClientPb.listUser                         avgt       3   4.752 ± 2.462   ms/op
ClientPb.createUser                     sample  234636   4.086 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.384           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.669           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.520           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.770           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.049           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  244548   3.924 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.452           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.374           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.987           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.839           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.278           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.670           ms/op
ClientPb.getUser                        sample  235124   4.079 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.596           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.480           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.651           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.904           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.179           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.408           ms/op
ClientPb.listUser                       sample  191676   5.005 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.032           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.865           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.289           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.290           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
