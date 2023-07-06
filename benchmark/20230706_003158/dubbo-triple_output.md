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
# Warmup Iteration   1: 1.131 ops/ms
# Warmup Iteration   2: 2.658 ops/ms
# Warmup Iteration   3: 5.725 ops/ms
Iteration   1: 5.658 ops/ms
Iteration   2: 5.946 ops/ms
Iteration   3: 6.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.899 ±(99.9%) 4.036 ops/ms [Average]
  (min, avg, max) = (5.658, 5.899, 6.093), stdev = 0.221
  CI (99.9%): [1.863, 9.935] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.756 ops/ms
# Warmup Iteration   2: 5.143 ops/ms
# Warmup Iteration   3: 6.029 ops/ms
Iteration   1: 6.308 ops/ms
Iteration   2: 6.255 ops/ms
Iteration   3: 6.058 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.207 ±(99.9%) 2.406 ops/ms [Average]
  (min, avg, max) = (6.058, 6.207, 6.308), stdev = 0.132
  CI (99.9%): [3.801, 8.612] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 4.776 ops/ms
# Warmup Iteration   3: 5.834 ops/ms
Iteration   1: 6.053 ops/ms
Iteration   2: 6.121 ops/ms
Iteration   3: 6.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.101 ±(99.9%) 0.764 ops/ms [Average]
  (min, avg, max) = (6.053, 6.101, 6.130), stdev = 0.042
  CI (99.9%): [5.338, 6.865] (assumes normal distribution)


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
# Warmup Iteration   1: 1.694 ops/ms
# Warmup Iteration   2: 4.368 ops/ms
# Warmup Iteration   3: 5.196 ops/ms
Iteration   1: 5.219 ops/ms
Iteration   2: 5.288 ops/ms
Iteration   3: 5.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.246 ±(99.9%) 0.662 ops/ms [Average]
  (min, avg, max) = (5.219, 5.246, 5.288), stdev = 0.036
  CI (99.9%): [4.585, 5.908] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.509 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.581 ±(99.9%) 0.015 ms/op
Iteration   1: 5.471 ±(99.9%) 0.008 ms/op
Iteration   2: 5.341 ±(99.9%) 0.008 ms/op
Iteration   3: 5.248 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.353 ±(99.9%) 2.048 ms/op [Average]
  (min, avg, max) = (5.248, 5.353, 5.471), stdev = 0.112
  CI (99.9%): [3.305, 7.401] (assumes normal distribution)


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
# Warmup Iteration   1: 14.930 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.618 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.138 ±(99.9%) 0.009 ms/op
Iteration   1: 5.032 ±(99.9%) 0.012 ms/op
Iteration   2: 5.101 ±(99.9%) 0.011 ms/op
Iteration   3: 5.078 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.070 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (5.032, 5.070, 5.101), stdev = 0.035
  CI (99.9%): [4.430, 5.710] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 17.206 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.239 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.281 ±(99.9%) 0.012 ms/op
Iteration   1: 5.307 ±(99.9%) 0.012 ms/op
Iteration   2: 5.314 ±(99.9%) 0.009 ms/op
Iteration   3: 5.147 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.256 ±(99.9%) 1.722 ms/op [Average]
  (min, avg, max) = (5.147, 5.256, 5.314), stdev = 0.094
  CI (99.9%): [3.534, 6.978] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 16.900 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 7.472 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.196 ±(99.9%) 0.012 ms/op
Iteration   1: 6.261 ±(99.9%) 0.019 ms/op
Iteration   2: 6.349 ±(99.9%) 0.013 ms/op
Iteration   3: 6.015 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.208 ±(99.9%) 3.163 ms/op [Average]
  (min, avg, max) = (6.015, 6.208, 6.349), stdev = 0.173
  CI (99.9%): [3.045, 9.371] (assumes normal distribution)


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
# Warmup Iteration   1: 15.475 ±(99.9%) 0.275 ms/op
# Warmup Iteration   2: 6.678 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.714 ±(99.9%) 0.025 ms/op
Iteration   1: 5.212 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.273 ms/op
                 createUser·p0.50:   5.005 ms/op
                 createUser·p0.90:   6.267 ms/op
                 createUser·p0.95:   6.971 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  17.564 ms/op
                 createUser·p0.9999: 23.242 ms/op
                 createUser·p1.00:   24.740 ms/op

Iteration   2: 5.386 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.294 ms/op
                 createUser·p0.50:   5.186 ms/op
                 createUser·p0.90:   6.554 ms/op
                 createUser·p0.95:   7.340 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  19.817 ms/op
                 createUser·p0.9999: 23.271 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 5.286 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   5.112 ms/op
                 createUser·p0.90:   6.349 ms/op
                 createUser·p0.95:   6.922 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  23.233 ms/op
                 createUser·p0.9999: 26.468 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181342
  mean =      5.294 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26 
    [ 2.500,  5.000) = 81099 
    [ 5.000,  7.500) = 93678 
    [ 7.500, 10.000) = 5229 
    [10.000, 12.500) = 789 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.078 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     20.010 ms/op
     p(99.9900) =     25.784 ms/op
     p(99.9990) =     27.052 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 15.465 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 6.017 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.284 ±(99.9%) 0.019 ms/op
Iteration   1: 5.134 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.876 ms/op
                 existUser·p0.50:   4.866 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.444 ms/op
                 existUser·p0.99:   10.154 ms/op
                 existUser·p0.999:  23.813 ms/op
                 existUser·p0.9999: 27.354 ms/op
                 existUser·p1.00:   36.045 ms/op

Iteration   2: 5.395 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.556 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.767 ms/op
                 existUser·p0.95:   7.569 ms/op
                 existUser·p0.99:   9.716 ms/op
                 existUser·p0.999:  25.042 ms/op
                 existUser·p0.9999: 29.962 ms/op
                 existUser·p1.00:   34.603 ms/op

Iteration   3: 4.928 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.200 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.676 ms/op
                 existUser·p0.99:   9.159 ms/op
                 existUser·p0.999:  23.240 ms/op
                 existUser·p0.9999: 34.571 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186462
  mean =      5.145 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 105471 
    [ 5.000,  7.500) = 72558 
    [ 7.500, 10.000) = 6883 
    [10.000, 12.500) = 846 
    [12.500, 15.000) = 394 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     24.037 ms/op
     p(99.9900) =     33.755 ms/op
     p(99.9990) =     34.912 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 16.078 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.298 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.746 ±(99.9%) 0.023 ms/op
Iteration   1: 5.576 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   7.119 ms/op
                 getUser·p0.95:   8.020 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  22.730 ms/op
                 getUser·p0.9999: 27.670 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   2: 5.410 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.747 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.234 ms/op
                 getUser·p0.99:   9.732 ms/op
                 getUser·p0.999:  15.057 ms/op
                 getUser·p0.9999: 29.393 ms/op
                 getUser·p1.00:   29.590 ms/op

Iteration   3: 5.336 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.519 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.529 ms/op
                 getUser·p0.95:   7.553 ms/op
                 getUser·p0.99:   10.444 ms/op
                 getUser·p0.999:  25.200 ms/op
                 getUser·p0.9999: 28.672 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176366
  mean =      5.439 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 73170 
    [ 5.000,  7.500) = 93328 
    [ 7.500, 10.000) = 7813 
    [10.000, 12.500) = 1506 
    [12.500, 15.000) = 311 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 89 

  Percentiles, ms/op:
      p(0.0000) =      1.747 ms/op
     p(50.0000) =      5.161 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     10.207 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 17.014 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 7.267 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.502 ±(99.9%) 0.028 ms/op
Iteration   1: 6.458 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   6.111 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.044 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  28.786 ms/op
                 listUser·p0.9999: 32.869 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 6.395 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   6.103 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.697 ms/op
                 listUser·p0.99:   11.809 ms/op
                 listUser·p0.999:  30.538 ms/op
                 listUser·p0.9999: 42.532 ms/op
                 listUser·p1.00:   45.679 ms/op

Iteration   3: 6.232 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.348 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  25.784 ms/op
                 listUser·p0.9999: 31.342 ms/op
                 listUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 150861
  mean =      6.360 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8685 
    [ 5.000, 10.000) = 138199 
    [10.000, 15.000) = 3523 
    [15.000, 20.000) = 142 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 152 
    [30.000, 35.000) = 63 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      2.028 ms/op
     p(50.0000) =      6.054 ms/op
     p(90.0000) =      7.635 ms/op
     p(95.0000) =      8.733 ms/op
     p(99.0000) =     11.829 ms/op
     p(99.9000) =     28.484 ms/op
     p(99.9900) =     41.325 ms/op
     p(99.9990) =     44.279 ms/op
     p(99.9999) =     45.679 ms/op
    p(100.0000) =     45.679 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.899 ± 4.036  ops/ms
ClientPb.existUser                       thrpt       3   6.207 ± 2.406  ops/ms
ClientPb.getUser                         thrpt       3   6.101 ± 0.764  ops/ms
ClientPb.listUser                        thrpt       3   5.246 ± 0.662  ops/ms
ClientPb.createUser                       avgt       3   5.353 ± 2.048   ms/op
ClientPb.existUser                        avgt       3   5.070 ± 0.640   ms/op
ClientPb.getUser                          avgt       3   5.256 ± 1.722   ms/op
ClientPb.listUser                         avgt       3   6.208 ± 3.163   ms/op
ClientPb.createUser                     sample  181342   5.294 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.880           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.398           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.078           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.322           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.010           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.784           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  186462   5.145 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.876           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.891           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.308           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.365           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.667           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.037           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.755           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.045           ms/op
ClientPb.getUser                        sample  176366   5.439 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.747           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.742           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.668           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.207           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.433           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.541           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.590           ms/op
ClientPb.listUser                       sample  150861   6.360 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.028           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.054           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.829           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.484           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.325           ms/op
ClientPb.listUser:listUser·p1.00        sample          45.679           ms/op
