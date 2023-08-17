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
# Warmup Iteration   1: 1.114 ops/ms
# Warmup Iteration   2: 2.776 ops/ms
# Warmup Iteration   3: 5.395 ops/ms
Iteration   1: 5.645 ops/ms
Iteration   2: 5.852 ops/ms
Iteration   3: 5.897 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.798 ±(99.9%) 2.449 ops/ms [Average]
  (min, avg, max) = (5.645, 5.798, 5.897), stdev = 0.134
  CI (99.9%): [3.349, 8.247] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.606 ops/ms
# Warmup Iteration   2: 5.250 ops/ms
# Warmup Iteration   3: 6.095 ops/ms
Iteration   1: 6.405 ops/ms
Iteration   2: 6.429 ops/ms
Iteration   3: 6.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.343 ±(99.9%) 2.351 ops/ms [Average]
  (min, avg, max) = (6.195, 6.343, 6.429), stdev = 0.129
  CI (99.9%): [3.992, 8.694] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.774 ops/ms
# Warmup Iteration   2: 4.436 ops/ms
# Warmup Iteration   3: 5.526 ops/ms
Iteration   1: 5.677 ops/ms
Iteration   2: 5.806 ops/ms
Iteration   3: 6.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.851 ±(99.9%) 3.651 ops/ms [Average]
  (min, avg, max) = (5.677, 5.851, 6.070), stdev = 0.200
  CI (99.9%): [2.200, 9.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 1.580 ops/ms
# Warmup Iteration   2: 4.083 ops/ms
# Warmup Iteration   3: 5.050 ops/ms
Iteration   1: 4.919 ops/ms
Iteration   2: 4.958 ops/ms
Iteration   3: 5.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.010 ±(99.9%) 2.293 ops/ms [Average]
  (min, avg, max) = (4.919, 5.010, 5.153), stdev = 0.126
  CI (99.9%): [2.717, 7.303] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.080 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 6.333 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.466 ±(99.9%) 0.020 ms/op
Iteration   1: 5.644 ±(99.9%) 0.018 ms/op
Iteration   2: 5.301 ±(99.9%) 0.017 ms/op
Iteration   3: 5.628 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.524 ±(99.9%) 3.534 ms/op [Average]
  (min, avg, max) = (5.301, 5.524, 5.644), stdev = 0.194
  CI (99.9%): [1.991, 9.058] (assumes normal distribution)


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
# Warmup Iteration   1: 15.339 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.567 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.433 ±(99.9%) 0.007 ms/op
Iteration   1: 5.115 ±(99.9%) 0.005 ms/op
Iteration   2: 4.975 ±(99.9%) 0.008 ms/op
Iteration   3: 5.014 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.035 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (4.975, 5.035, 5.115), stdev = 0.072
  CI (99.9%): [3.720, 6.349] (assumes normal distribution)


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
# Warmup Iteration   1: 16.438 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 6.051 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.622 ±(99.9%) 0.013 ms/op
Iteration   1: 5.575 ±(99.9%) 0.006 ms/op
Iteration   2: 5.466 ±(99.9%) 0.013 ms/op
Iteration   3: 5.334 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.459 ±(99.9%) 2.206 ms/op [Average]
  (min, avg, max) = (5.334, 5.459, 5.575), stdev = 0.121
  CI (99.9%): [3.253, 7.664] (assumes normal distribution)


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
# Warmup Iteration   1: 18.631 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 7.467 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.264 ±(99.9%) 0.015 ms/op
Iteration   1: 6.316 ±(99.9%) 0.014 ms/op
Iteration   2: 6.503 ±(99.9%) 0.013 ms/op
Iteration   3: 6.532 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.450 ±(99.9%) 2.133 ms/op [Average]
  (min, avg, max) = (6.316, 6.450, 6.532), stdev = 0.117
  CI (99.9%): [4.318, 8.583] (assumes normal distribution)


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
# Warmup Iteration   1: 16.041 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.653 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.093 ±(99.9%) 0.031 ms/op
Iteration   1: 5.414 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.954 ms/op
                 createUser·p0.50:   5.054 ms/op
                 createUser·p0.90:   7.053 ms/op
                 createUser·p0.95:   8.233 ms/op
                 createUser·p0.99:   11.023 ms/op
                 createUser·p0.999:  25.023 ms/op
                 createUser·p0.9999: 34.233 ms/op
                 createUser·p1.00:   35.586 ms/op

Iteration   2: 5.397 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.980 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.865 ms/op
                 createUser·p0.95:   7.864 ms/op
                 createUser·p0.99:   10.338 ms/op
                 createUser·p0.999:  26.669 ms/op
                 createUser·p0.9999: 30.678 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   3: 5.245 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.142 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.676 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   9.781 ms/op
                 createUser·p0.999:  25.985 ms/op
                 createUser·p0.9999: 30.730 ms/op
                 createUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 179389
  mean =      5.351 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 86988 
    [ 5.000,  7.500) = 81259 
    [ 7.500, 10.000) = 8755 
    [10.000, 12.500) = 1741 
    [12.500, 15.000) = 258 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.954 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.849 ms/op
     p(95.0000) =      7.864 ms/op
     p(99.0000) =     10.437 ms/op
     p(99.9000) =     25.939 ms/op
     p(99.9900) =     32.866 ms/op
     p(99.9990) =     35.118 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 14.567 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.508 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.261 ±(99.9%) 0.020 ms/op
Iteration   1: 5.287 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.627 ms/op
                 existUser·p0.95:   7.635 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  23.922 ms/op
                 existUser·p0.9999: 35.717 ms/op
                 existUser·p1.00:   36.831 ms/op

Iteration   2: 5.101 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.003 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.541 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   9.912 ms/op
                 existUser·p0.999:  23.443 ms/op
                 existUser·p0.9999: 26.271 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 5.077 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.167 ms/op
                 existUser·p0.50:   4.776 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.324 ms/op
                 existUser·p0.99:   10.767 ms/op
                 existUser·p0.999:  29.635 ms/op
                 existUser·p0.9999: 34.946 ms/op
                 existUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 186172
  mean =      5.153 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 108241 
    [ 5.000,  7.500) = 68525 
    [ 7.500, 10.000) = 7195 
    [10.000, 12.500) = 1300 
    [12.500, 15.000) = 474 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 42 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.504 ms/op
     p(99.0000) =     10.322 ms/op
     p(99.9000) =     23.882 ms/op
     p(99.9900) =     33.927 ms/op
     p(99.9990) =     36.718 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 16.586 ±(99.9%) 0.263 ms/op
# Warmup Iteration   2: 6.356 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.618 ±(99.9%) 0.021 ms/op
Iteration   1: 5.742 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.294 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   7.610 ms/op
                 getUser·p0.95:   8.978 ms/op
                 getUser·p0.99:   12.583 ms/op
                 getUser·p0.999:  25.031 ms/op
                 getUser·p0.9999: 36.532 ms/op
                 getUser·p1.00:   36.831 ms/op

Iteration   2: 5.178 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.478 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   6.414 ms/op
                 getUser·p0.95:   7.610 ms/op
                 getUser·p0.99:   10.658 ms/op
                 getUser·p0.999:  23.724 ms/op
                 getUser·p0.9999: 28.235 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   3: 5.550 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.179 ms/op
                 getUser·p0.50:   5.112 ms/op
                 getUser·p0.90:   7.356 ms/op
                 getUser·p0.95:   8.733 ms/op
                 getUser·p0.99:   12.860 ms/op
                 getUser·p0.999:  26.739 ms/op
                 getUser·p0.9999: 29.579 ms/op
                 getUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175060
  mean =      5.480 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 81851 
    [ 5.000,  7.500) = 78569 
    [ 7.500, 10.000) = 10571 
    [10.000, 12.500) = 2540 
    [12.500, 15.000) = 858 
    [15.000, 17.500) = 282 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 74 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     24.443 ms/op
     p(99.9900) =     34.472 ms/op
     p(99.9990) =     36.782 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 18.451 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 7.701 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.343 ±(99.9%) 0.026 ms/op
Iteration   1: 6.618 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   6.185 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.880 ms/op
                 listUser·p0.99:   14.006 ms/op
                 listUser·p0.999:  29.612 ms/op
                 listUser·p0.9999: 36.384 ms/op
                 listUser·p1.00:   36.766 ms/op

Iteration   2: 6.341 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.544 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.948 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   13.730 ms/op
                 listUser·p0.999:  26.968 ms/op
                 listUser·p0.9999: 29.534 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   3: 6.378 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.979 ms/op
                 listUser·p0.95:   9.634 ms/op
                 listUser·p0.99:   13.284 ms/op
                 listUser·p0.999:  23.945 ms/op
                 listUser·p0.9999: 28.180 ms/op
                 listUser·p1.00:   29.164 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148920
  mean =      6.443 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 13148 
    [ 5.000,  7.500) = 115075 
    [ 7.500, 10.000) = 14431 
    [10.000, 12.500) = 4056 
    [12.500, 15.000) = 1126 
    [15.000, 17.500) = 478 
    [17.500, 20.000) = 215 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 123 
    [27.500, 30.000) = 91 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      6.029 ms/op
     p(90.0000) =      8.151 ms/op
     p(95.0000) =      9.634 ms/op
     p(99.0000) =     13.664 ms/op
     p(99.9000) =     27.102 ms/op
     p(99.9900) =     36.052 ms/op
     p(99.9990) =     36.670 ms/op
     p(99.9999) =     36.766 ms/op
    p(100.0000) =     36.766 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.798 ± 2.449  ops/ms
ClientPb.existUser                       thrpt       3   6.343 ± 2.351  ops/ms
ClientPb.getUser                         thrpt       3   5.851 ± 3.651  ops/ms
ClientPb.listUser                        thrpt       3   5.010 ± 2.293  ops/ms
ClientPb.createUser                       avgt       3   5.524 ± 3.534   ms/op
ClientPb.existUser                        avgt       3   5.035 ± 1.314   ms/op
ClientPb.getUser                          avgt       3   5.459 ± 2.206   ms/op
ClientPb.listUser                         avgt       3   6.450 ± 2.133   ms/op
ClientPb.createUser                     sample  179389   5.351 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.954           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.030           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.849           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.864           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.437           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.939           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.866           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.586           ms/op
ClientPb.existUser                      sample  186172   5.153 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.965           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.504           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.322           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.882           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.927           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.831           ms/op
ClientPb.getUser                        sample  175060   5.480 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.179           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.503           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.124           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.443           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.472           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.831           ms/op
ClientPb.listUser                       sample  148920   6.443 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.272           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.029           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.151           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.634           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.664           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.102           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.052           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.766           ms/op
