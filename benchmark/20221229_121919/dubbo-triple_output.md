# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.244 ops/ms
# Warmup Iteration   2: 3.018 ops/ms
# Warmup Iteration   3: 6.148 ops/ms
Iteration   1: 6.108 ops/ms
Iteration   2: 6.199 ops/ms
Iteration   3: 6.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.295 ±(99.9%) 4.562 ops/ms [Average]
  (min, avg, max) = (6.108, 6.295, 6.579), stdev = 0.250
  CI (99.9%): [1.733, 10.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.870 ops/ms
# Warmup Iteration   2: 5.880 ops/ms
# Warmup Iteration   3: 6.902 ops/ms
Iteration   1: 6.802 ops/ms
Iteration   2: 6.579 ops/ms
Iteration   3: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.797 ±(99.9%) 3.939 ops/ms [Average]
  (min, avg, max) = (6.579, 6.797, 7.010), stdev = 0.216
  CI (99.9%): [2.858, 10.736] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.803 ops/ms
# Warmup Iteration   2: 5.239 ops/ms
# Warmup Iteration   3: 6.376 ops/ms
Iteration   1: 6.210 ops/ms
Iteration   2: 6.207 ops/ms
Iteration   3: 6.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.317 ±(99.9%) 3.414 ops/ms [Average]
  (min, avg, max) = (6.207, 6.317, 6.533), stdev = 0.187
  CI (99.9%): [2.902, 9.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 5.040 ops/ms
# Warmup Iteration   3: 5.619 ops/ms
Iteration   1: 5.388 ops/ms
Iteration   2: 5.179 ops/ms
Iteration   3: 5.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.391 ±(99.9%) 3.896 ops/ms [Average]
  (min, avg, max) = (5.179, 5.391, 5.606), stdev = 0.214
  CI (99.9%): [1.495, 9.286] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 16.058 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.756 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.213 ±(99.9%) 0.020 ms/op
Iteration   1: 5.270 ±(99.9%) 0.007 ms/op
Iteration   2: 5.031 ±(99.9%) 0.023 ms/op
Iteration   3: 5.095 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.132 ±(99.9%) 2.255 ms/op [Average]
  (min, avg, max) = (5.031, 5.132, 5.270), stdev = 0.124
  CI (99.9%): [2.877, 7.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 16.625 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.589 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.070 ±(99.9%) 0.005 ms/op
Iteration   1: 4.839 ±(99.9%) 0.018 ms/op
Iteration   2: 4.929 ±(99.9%) 0.008 ms/op
Iteration   3: 4.913 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.894 ±(99.9%) 0.871 ms/op [Average]
  (min, avg, max) = (4.839, 4.894, 4.929), stdev = 0.048
  CI (99.9%): [4.022, 5.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 15.939 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.017 ±(99.9%) 0.009 ms/op
Iteration   1: 5.162 ±(99.9%) 0.014 ms/op
Iteration   2: 5.081 ±(99.9%) 0.012 ms/op
Iteration   3: 5.092 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.112 ±(99.9%) 0.805 ms/op [Average]
  (min, avg, max) = (5.081, 5.112, 5.162), stdev = 0.044
  CI (99.9%): [4.306, 5.917] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.383 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.724 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.368 ±(99.9%) 0.006 ms/op
Iteration   1: 6.150 ±(99.9%) 0.012 ms/op
Iteration   2: 5.894 ±(99.9%) 0.013 ms/op
Iteration   3: 5.686 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.910 ±(99.9%) 4.238 ms/op [Average]
  (min, avg, max) = (5.686, 5.910, 6.150), stdev = 0.232
  CI (99.9%): [1.672, 10.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 16.446 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.965 ±(99.9%) 0.068 ms/op
# Warmup Iteration   3: 5.356 ±(99.9%) 0.022 ms/op
Iteration   1: 5.310 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.946 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.348 ms/op
                 createUser·p0.99:   10.453 ms/op
                 createUser·p0.999:  22.282 ms/op
                 createUser·p0.9999: 25.717 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   2: 5.182 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.909 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.430 ms/op
                 createUser·p0.99:   10.024 ms/op
                 createUser·p0.999:  23.790 ms/op
                 createUser·p0.9999: 27.913 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 5.176 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.259 ms/op
                 createUser·p0.95:   7.029 ms/op
                 createUser·p0.99:   10.037 ms/op
                 createUser·p0.999:  26.149 ms/op
                 createUser·p0.9999: 32.854 ms/op
                 createUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 183760
  mean =      5.222 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 96050 
    [ 5.000,  7.500) = 79524 
    [ 7.500, 10.000) = 6096 
    [10.000, 12.500) = 1186 
    [12.500, 15.000) = 429 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.552 ms/op
     p(50.0000) =      4.956 ms/op
     p(90.0000) =      6.446 ms/op
     p(95.0000) =      7.274 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     22.741 ms/op
     p(99.9900) =     31.506 ms/op
     p(99.9990) =     33.417 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.247 ±(99.9%) 0.259 ms/op
# Warmup Iteration   2: 5.792 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.018 ms/op
Iteration   1: 4.997 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.286 ms/op
                 existUser·p0.50:   4.801 ms/op
                 existUser·p0.90:   5.923 ms/op
                 existUser·p0.95:   6.569 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  19.856 ms/op
                 existUser·p0.9999: 29.412 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   2: 5.136 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.122 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.218 ms/op
                 existUser·p0.95:   7.184 ms/op
                 existUser·p0.99:   9.961 ms/op
                 existUser·p0.999:  23.970 ms/op
                 existUser·p0.9999: 29.698 ms/op
                 existUser·p1.00:   31.392 ms/op

Iteration   3: 5.191 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   6.865 ms/op
                 existUser·p0.99:   9.028 ms/op
                 existUser·p0.999:  26.581 ms/op
                 existUser·p0.9999: 31.671 ms/op
                 existUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187924
  mean =      5.107 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 106075 
    [ 5.000,  7.500) = 75910 
    [ 7.500, 10.000) = 4374 
    [10.000, 12.500) = 887 
    [12.500, 15.000) = 305 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      9.646 ms/op
     p(99.9000) =     20.979 ms/op
     p(99.9900) =     30.266 ms/op
     p(99.9990) =     32.088 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.707 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 5.966 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.318 ±(99.9%) 0.018 ms/op
Iteration   1: 5.103 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   6.939 ms/op
                 getUser·p0.99:   9.224 ms/op
                 getUser·p0.999:  19.617 ms/op
                 getUser·p0.9999: 24.901 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 5.280 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.654 ms/op
                 getUser·p0.50:   4.964 ms/op
                 getUser·p0.90:   6.540 ms/op
                 getUser·p0.95:   7.799 ms/op
                 getUser·p0.99:   10.825 ms/op
                 getUser·p0.999:  21.836 ms/op
                 getUser·p0.9999: 24.410 ms/op
                 getUser·p1.00:   25.592 ms/op

Iteration   3: 5.073 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   6.062 ms/op
                 getUser·p0.95:   6.750 ms/op
                 getUser·p0.99:   9.058 ms/op
                 getUser·p0.999:  21.200 ms/op
                 getUser·p0.9999: 27.253 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 186307
  mean =      5.151 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 102547 
    [ 5.000,  7.500) = 76496 
    [ 7.500, 10.000) = 5598 
    [10.000, 12.500) = 970 
    [12.500, 15.000) = 387 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.849 ms/op
     p(50.0000) =      4.915 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.111 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.524 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.975 ±(99.9%) 0.255 ms/op
# Warmup Iteration   2: 6.564 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 6.296 ±(99.9%) 0.025 ms/op
Iteration   1: 5.969 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.724 ms/op
                 listUser·p0.50:   5.603 ms/op
                 listUser·p0.90:   7.234 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.361 ms/op
                 listUser·p0.999:  23.753 ms/op
                 listUser·p0.9999: 27.205 ms/op
                 listUser·p1.00:   27.656 ms/op

Iteration   2: 6.069 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   5.775 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.233 ms/op
                 listUser·p0.99:   12.643 ms/op
                 listUser·p0.999:  27.451 ms/op
                 listUser·p0.9999: 34.520 ms/op
                 listUser·p1.00:   35.062 ms/op

Iteration   3: 6.187 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.332 ms/op
                 listUser·p0.95:   8.380 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  22.679 ms/op
                 listUser·p0.9999: 26.990 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157913
  mean =      6.074 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 14694 
    [ 5.000,  7.500) = 130534 
    [ 7.500, 10.000) = 9210 
    [10.000, 12.500) = 2374 
    [12.500, 15.000) = 524 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.509 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      7.184 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     31.430 ms/op
     p(99.9990) =     34.910 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.295 ± 4.562  ops/ms
ClientPb.existUser                       thrpt       3   6.797 ± 3.939  ops/ms
ClientPb.getUser                         thrpt       3   6.317 ± 3.414  ops/ms
ClientPb.listUser                        thrpt       3   5.391 ± 3.896  ops/ms
ClientPb.createUser                       avgt       3   5.132 ± 2.255   ms/op
ClientPb.existUser                        avgt       3   4.894 ± 0.871   ms/op
ClientPb.getUser                          avgt       3   5.112 ± 0.805   ms/op
ClientPb.listUser                         avgt       3   5.910 ± 4.238   ms/op
ClientPb.createUser                     sample  183760   5.222 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.552           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.956           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.446           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.274           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.174           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.741           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.506           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.554           ms/op
ClientPb.existUser                      sample  187924   5.107 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.384           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.136           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.646           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.979           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.266           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.145           ms/op
ClientPb.getUser                        sample  186307   5.151 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.111           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.732           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.592           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  157913   6.074 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.509           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.567           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.576           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.430           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.062           ms/op
