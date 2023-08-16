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
# Warmup Iteration   1: 1.348 ops/ms
# Warmup Iteration   2: 3.388 ops/ms
# Warmup Iteration   3: 6.252 ops/ms
Iteration   1: 5.989 ops/ms
Iteration   2: 6.608 ops/ms
Iteration   3: 6.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.282 ±(99.9%) 5.674 ops/ms [Average]
  (min, avg, max) = (5.989, 6.282, 6.608), stdev = 0.311
  CI (99.9%): [0.608, 11.956] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.047 ops/ms
# Warmup Iteration   2: 5.425 ops/ms
# Warmup Iteration   3: 6.843 ops/ms
Iteration   1: 7.013 ops/ms
Iteration   2: 6.914 ops/ms
Iteration   3: 7.074 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.000 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (6.914, 7.000, 7.074), stdev = 0.081
  CI (99.9%): [5.527, 8.474] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.816 ops/ms
# Warmup Iteration   2: 5.546 ops/ms
# Warmup Iteration   3: 6.657 ops/ms
Iteration   1: 6.594 ops/ms
Iteration   2: 6.526 ops/ms
Iteration   3: 6.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.508 ±(99.9%) 1.783 ops/ms [Average]
  (min, avg, max) = (6.402, 6.508, 6.594), stdev = 0.098
  CI (99.9%): [4.725, 8.290] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.922 ops/ms
# Warmup Iteration   2: 4.730 ops/ms
# Warmup Iteration   3: 5.783 ops/ms
Iteration   1: 5.686 ops/ms
Iteration   2: 5.446 ops/ms
Iteration   3: 5.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.542 ±(99.9%) 2.317 ops/ms [Average]
  (min, avg, max) = (5.446, 5.542, 5.686), stdev = 0.127
  CI (99.9%): [3.225, 7.859] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 16.750 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.031 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.145 ±(99.9%) 0.009 ms/op
Iteration   1: 5.097 ±(99.9%) 0.010 ms/op
Iteration   2: 5.120 ±(99.9%) 0.005 ms/op
Iteration   3: 4.876 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.031 ±(99.9%) 2.456 ms/op [Average]
  (min, avg, max) = (4.876, 5.031, 5.120), stdev = 0.135
  CI (99.9%): [2.576, 7.487] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.646 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.896 ±(99.9%) 0.005 ms/op
Iteration   1: 4.657 ±(99.9%) 0.013 ms/op
Iteration   2: 4.759 ±(99.9%) 0.007 ms/op
Iteration   3: 4.757 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.724 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (4.657, 4.724, 4.759), stdev = 0.058
  CI (99.9%): [3.662, 5.786] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.484 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.692 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.916 ±(99.9%) 0.009 ms/op
Iteration   1: 4.903 ±(99.9%) 0.006 ms/op
Iteration   2: 5.065 ±(99.9%) 0.006 ms/op
Iteration   3: 4.982 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.983 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (4.903, 4.983, 5.065), stdev = 0.081
  CI (99.9%): [3.505, 6.462] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.868 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 6.558 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.931 ±(99.9%) 0.010 ms/op
Iteration   1: 5.587 ±(99.9%) 0.017 ms/op
Iteration   2: 5.719 ±(99.9%) 0.015 ms/op
Iteration   3: 5.449 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.585 ±(99.9%) 2.463 ms/op [Average]
  (min, avg, max) = (5.449, 5.585, 5.719), stdev = 0.135
  CI (99.9%): [3.122, 8.048] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 13.036 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.908 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.537 ±(99.9%) 0.022 ms/op
Iteration   1: 5.014 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   4.743 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   7.111 ms/op
                 createUser·p0.99:   9.361 ms/op
                 createUser·p0.999:  18.222 ms/op
                 createUser·p0.9999: 25.616 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 5.146 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   6.382 ms/op
                 createUser·p0.95:   7.234 ms/op
                 createUser·p0.99:   9.814 ms/op
                 createUser·p0.999:  19.553 ms/op
                 createUser·p0.9999: 25.657 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 5.031 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   4.784 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   7.062 ms/op
                 createUser·p0.99:   9.683 ms/op
                 createUser·p0.999:  21.961 ms/op
                 createUser·p0.9999: 24.934 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189638
  mean =      5.063 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 115 
    [ 2.500,  5.000) = 112390 
    [ 5.000,  7.500) = 69890 
    [ 7.500, 10.000) = 5735 
    [10.000, 12.500) = 996 
    [12.500, 15.000) = 271 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      9.585 ms/op
     p(99.9000) =     19.017 ms/op
     p(99.9900) =     25.334 ms/op
     p(99.9990) =     27.121 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 15.122 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.015 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.016 ms/op
Iteration   1: 5.025 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.360 ms/op
                 existUser·p0.50:   4.784 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.143 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  19.707 ms/op
                 existUser·p0.9999: 28.243 ms/op
                 existUser·p1.00:   29.295 ms/op

Iteration   2: 4.854 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   5.882 ms/op
                 existUser·p0.95:   6.701 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 25.526 ms/op
                 existUser·p1.00:   26.182 ms/op

Iteration   3: 5.026 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.169 ms/op
                 existUser·p0.95:   6.874 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  20.851 ms/op
                 existUser·p0.9999: 27.075 ms/op
                 existUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193232
  mean =      4.967 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 124 
    [ 2.500,  5.000) = 124806 
    [ 5.000,  7.500) = 61814 
    [ 7.500, 10.000) = 4756 
    [10.000, 12.500) = 1117 
    [12.500, 15.000) = 321 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.360 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.095 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      9.765 ms/op
     p(99.9000) =     19.043 ms/op
     p(99.9900) =     27.875 ms/op
     p(99.9990) =     29.233 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 16.936 ±(99.9%) 0.274 ms/op
# Warmup Iteration   2: 5.950 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.413 ±(99.9%) 0.021 ms/op
Iteration   1: 5.167 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.785 ms/op
                 getUser·p0.50:   4.915 ms/op
                 getUser·p0.90:   6.226 ms/op
                 getUser·p0.95:   7.004 ms/op
                 getUser·p0.99:   10.354 ms/op
                 getUser·p0.999:  22.187 ms/op
                 getUser·p0.9999: 28.641 ms/op
                 getUser·p1.00:   29.393 ms/op

Iteration   2: 5.198 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   4.923 ms/op
                 getUser·p0.90:   6.275 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   10.961 ms/op
                 getUser·p0.999:  22.744 ms/op
                 getUser·p0.9999: 27.520 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 5.178 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.021 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.005 ms/op
                 getUser·p0.95:   6.717 ms/op
                 getUser·p0.99:   10.142 ms/op
                 getUser·p0.999:  29.336 ms/op
                 getUser·p0.9999: 33.674 ms/op
                 getUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 185104
  mean =      5.181 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 99911 
    [ 5.000,  7.500) = 78351 
    [ 7.500, 10.000) = 4708 
    [10.000, 12.500) = 1254 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 229 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.021 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =     10.469 ms/op
     p(99.9000) =     22.436 ms/op
     p(99.9900) =     32.997 ms/op
     p(99.9990) =     34.698 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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
# Warmup Iteration   1: 18.306 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 6.934 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.269 ±(99.9%) 0.028 ms/op
Iteration   1: 5.676 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.678 ms/op
                 listUser·p0.999:  23.877 ms/op
                 listUser·p0.9999: 26.833 ms/op
                 listUser·p1.00:   28.705 ms/op

Iteration   2: 5.956 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.716 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   12.419 ms/op
                 listUser·p0.999:  27.723 ms/op
                 listUser·p0.9999: 35.162 ms/op
                 listUser·p1.00:   35.586 ms/op

Iteration   3: 5.898 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.152 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   11.496 ms/op
                 listUser·p0.999:  19.063 ms/op
                 listUser·p0.9999: 24.314 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164231
  mean =      5.841 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 36267 
    [ 5.000,  7.500) = 115268 
    [ 7.500, 10.000) = 9128 
    [10.000, 12.500) = 2323 
    [12.500, 15.000) = 694 
    [15.000, 17.500) = 186 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.862 ms/op
     p(99.9000) =     23.096 ms/op
     p(99.9900) =     33.949 ms/op
     p(99.9990) =     35.502 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.282 ± 5.674  ops/ms
ClientPb.existUser                       thrpt       3   7.000 ± 1.474  ops/ms
ClientPb.getUser                         thrpt       3   6.508 ± 1.783  ops/ms
ClientPb.listUser                        thrpt       3   5.542 ± 2.317  ops/ms
ClientPb.createUser                       avgt       3   5.031 ± 2.456   ms/op
ClientPb.existUser                        avgt       3   4.724 ± 1.062   ms/op
ClientPb.getUser                          avgt       3   4.983 ± 1.479   ms/op
ClientPb.listUser                         avgt       3   5.585 ± 2.463   ms/op
ClientPb.createUser                     sample  189638   5.063 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.708           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.308           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.143           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.585           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.017           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.334           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.591           ms/op
ClientPb.existUser                      sample  193232   4.967 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.360           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.095           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.922           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.765           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.043           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.875           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.295           ms/op
ClientPb.getUser                        sample  185104   5.181 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.021           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.469           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.436           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.997           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.865           ms/op
ClientPb.listUser                       sample  164231   5.841 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.253           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.102           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.862           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.096           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.949           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.586           ms/op
