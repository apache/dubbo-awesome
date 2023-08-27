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
# Warmup Iteration   1: 1.302 ops/ms
# Warmup Iteration   2: 2.996 ops/ms
# Warmup Iteration   3: 5.878 ops/ms
Iteration   1: 5.948 ops/ms
Iteration   2: 6.143 ops/ms
Iteration   3: 6.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.167 ±(99.9%) 4.221 ops/ms [Average]
  (min, avg, max) = (5.948, 6.167, 6.409), stdev = 0.231
  CI (99.9%): [1.946, 10.388] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.807 ops/ms
# Warmup Iteration   2: 5.309 ops/ms
# Warmup Iteration   3: 6.083 ops/ms
Iteration   1: 6.433 ops/ms
Iteration   2: 6.219 ops/ms
Iteration   3: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.396 ±(99.9%) 2.945 ops/ms [Average]
  (min, avg, max) = (6.219, 6.396, 6.535), stdev = 0.161
  CI (99.9%): [3.451, 9.340] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.744 ops/ms
# Warmup Iteration   2: 5.439 ops/ms
# Warmup Iteration   3: 6.249 ops/ms
Iteration   1: 6.077 ops/ms
Iteration   2: 6.135 ops/ms
Iteration   3: 6.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.147 ±(99.9%) 1.416 ops/ms [Average]
  (min, avg, max) = (6.077, 6.147, 6.231), stdev = 0.078
  CI (99.9%): [4.731, 7.564] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.879 ops/ms
# Warmup Iteration   2: 4.394 ops/ms
# Warmup Iteration   3: 5.231 ops/ms
Iteration   1: 5.156 ops/ms
Iteration   2: 5.223 ops/ms
Iteration   3: 5.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.272 ±(99.9%) 2.687 ops/ms [Average]
  (min, avg, max) = (5.156, 5.272, 5.438), stdev = 0.147
  CI (99.9%): [2.586, 7.959] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 16.378 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.362 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.693 ±(99.9%) 0.009 ms/op
Iteration   1: 5.263 ±(99.9%) 0.011 ms/op
Iteration   2: 5.247 ±(99.9%) 0.009 ms/op
Iteration   3: 5.129 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.213 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (5.129, 5.213, 5.263), stdev = 0.073
  CI (99.9%): [3.876, 6.550] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.261 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.761 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.201 ±(99.9%) 0.004 ms/op
Iteration   1: 5.132 ±(99.9%) 0.007 ms/op
Iteration   2: 4.911 ±(99.9%) 0.021 ms/op
Iteration   3: 5.021 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.021 ±(99.9%) 2.016 ms/op [Average]
  (min, avg, max) = (4.911, 5.021, 5.132), stdev = 0.111
  CI (99.9%): [3.005, 7.037] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.099 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 6.353 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.215 ±(99.9%) 0.022 ms/op
Iteration   1: 5.354 ±(99.9%) 0.015 ms/op
Iteration   2: 5.270 ±(99.9%) 0.014 ms/op
Iteration   3: 5.245 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.290 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (5.245, 5.290, 5.354), stdev = 0.057
  CI (99.9%): [4.248, 6.332] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.633 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 7.163 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.119 ±(99.9%) 0.019 ms/op
Iteration   1: 5.873 ±(99.9%) 0.010 ms/op
Iteration   2: 5.997 ±(99.9%) 0.022 ms/op
Iteration   3: 6.062 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.977 ±(99.9%) 1.750 ms/op [Average]
  (min, avg, max) = (5.873, 5.977, 6.062), stdev = 0.096
  CI (99.9%): [4.228, 7.727] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.658 ±(99.9%) 0.305 ms/op
# Warmup Iteration   2: 6.678 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.835 ±(99.9%) 0.026 ms/op
Iteration   1: 5.460 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.195 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.799 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   10.011 ms/op
                 createUser·p0.999:  21.308 ms/op
                 createUser·p0.9999: 25.896 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   2: 5.260 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.118 ms/op
                 createUser·p0.50:   5.038 ms/op
                 createUser·p0.90:   6.545 ms/op
                 createUser·p0.95:   7.274 ms/op
                 createUser·p0.99:   9.421 ms/op
                 createUser·p0.999:  23.583 ms/op
                 createUser·p0.9999: 30.537 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   3: 5.187 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.003 ms/op
                 createUser·p0.50:   4.948 ms/op
                 createUser·p0.90:   6.439 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   9.716 ms/op
                 createUser·p0.999:  23.597 ms/op
                 createUser·p0.9999: 27.285 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 180974
  mean =      5.300 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 84363 
    [ 5.000,  7.500) = 88298 
    [ 7.500, 10.000) = 6647 
    [10.000, 12.500) = 1075 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.003 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =      9.732 ms/op
     p(99.9000) =     21.923 ms/op
     p(99.9900) =     28.079 ms/op
     p(99.9990) =     30.899 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 15.970 ±(99.9%) 0.244 ms/op
# Warmup Iteration   2: 5.497 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.337 ±(99.9%) 0.022 ms/op
Iteration   1: 5.395 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.066 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.808 ms/op
                 existUser·p0.95:   8.110 ms/op
                 existUser·p0.99:   10.650 ms/op
                 existUser·p0.999:  20.775 ms/op
                 existUser·p0.9999: 25.144 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 4.935 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.978 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.029 ms/op
                 existUser·p0.95:   6.750 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  16.473 ms/op
                 existUser·p0.9999: 29.852 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 5.159 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.966 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   7.193 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  16.170 ms/op
                 existUser·p0.9999: 34.655 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186044
  mean =      5.156 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 102717 
    [ 5.000,  7.500) = 74743 
    [ 7.500, 10.000) = 6544 
    [10.000, 12.500) = 1444 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.390 ms/op
     p(95.0000) =      7.340 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     33.620 ms/op
     p(99.9990) =     35.220 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.531 ±(99.9%) 0.264 ms/op
# Warmup Iteration   2: 6.137 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.423 ±(99.9%) 0.020 ms/op
Iteration   1: 5.307 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.208 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.488 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   12.363 ms/op
                 getUser·p0.999:  22.496 ms/op
                 getUser·p0.9999: 30.342 ms/op
                 getUser·p1.00:   33.325 ms/op

Iteration   2: 5.529 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   6.799 ms/op
                 getUser·p0.95:   8.028 ms/op
                 getUser·p0.99:   11.059 ms/op
                 getUser·p0.999:  24.196 ms/op
                 getUser·p0.9999: 27.866 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 5.379 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.458 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.127 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  27.132 ms/op
                 getUser·p0.9999: 33.325 ms/op
                 getUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177497
  mean =      5.403 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 76515 
    [ 5.000,  7.500) = 91379 
    [ 7.500, 10.000) = 6967 
    [10.000, 12.500) = 1547 
    [12.500, 15.000) = 588 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      6.562 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     23.495 ms/op
     p(99.9900) =     32.637 ms/op
     p(99.9990) =     34.108 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 16.226 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.545 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.491 ±(99.9%) 0.026 ms/op
Iteration   1: 6.256 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.528 ms/op
                 listUser·p0.95:   8.880 ms/op
                 listUser·p0.99:   13.187 ms/op
                 listUser·p0.999:  27.798 ms/op
                 listUser·p0.9999: 32.175 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   2: 6.226 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.331 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  26.164 ms/op
                 listUser·p0.9999: 31.060 ms/op
                 listUser·p1.00:   32.866 ms/op

Iteration   3: 5.837 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.253 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  19.048 ms/op
                 listUser·p0.9999: 21.595 ms/op
                 listUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157344
  mean =      6.100 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 20457 
    [ 5.000,  7.500) = 123246 
    [ 7.500, 10.000) = 10012 
    [10.000, 12.500) = 2241 
    [12.500, 15.000) = 658 
    [15.000, 17.500) = 334 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.134 ms/op
     p(50.0000) =      5.800 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     25.384 ms/op
     p(99.9900) =     31.007 ms/op
     p(99.9990) =     32.697 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.167 ± 4.221  ops/ms
ClientPb.existUser                       thrpt       3   6.396 ± 2.945  ops/ms
ClientPb.getUser                         thrpt       3   6.147 ± 1.416  ops/ms
ClientPb.listUser                        thrpt       3   5.272 ± 2.687  ops/ms
ClientPb.createUser                       avgt       3   5.213 ± 1.337   ms/op
ClientPb.existUser                        avgt       3   5.021 ± 2.016   ms/op
ClientPb.getUser                          avgt       3   5.290 ± 1.042   ms/op
ClientPb.listUser                         avgt       3   5.977 ± 1.750   ms/op
ClientPb.createUser                     sample  180974   5.300 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.003           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.079           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.611           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.397           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.732           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.923           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.079           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  186044   5.156 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.966           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.390           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.340           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.125           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.620           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  177497   5.403 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.208           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.136           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.651           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.495           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.637           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  157344   6.100 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.134           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.324           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.993           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.384           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.007           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.866           ms/op
