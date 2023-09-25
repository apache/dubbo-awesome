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
# Warmup Iteration   1: 0.889 ops/ms
# Warmup Iteration   2: 2.058 ops/ms
# Warmup Iteration   3: 4.925 ops/ms
Iteration   1: 5.538 ops/ms
Iteration   2: 5.708 ops/ms
Iteration   3: 5.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.695 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (5.538, 5.695, 5.840), stdev = 0.151
  CI (99.9%): [2.939, 8.451] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.534 ops/ms
# Warmup Iteration   2: 4.498 ops/ms
# Warmup Iteration   3: 5.978 ops/ms
Iteration   1: 5.876 ops/ms
Iteration   2: 6.026 ops/ms
Iteration   3: 6.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.011 ±(99.9%) 2.334 ops/ms [Average]
  (min, avg, max) = (5.876, 6.011, 6.131), stdev = 0.128
  CI (99.9%): [3.677, 8.345] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.881 ops/ms
# Warmup Iteration   2: 4.304 ops/ms
# Warmup Iteration   3: 5.475 ops/ms
Iteration   1: 5.355 ops/ms
Iteration   2: 5.670 ops/ms
Iteration   3: 5.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.651 ±(99.9%) 5.237 ops/ms [Average]
  (min, avg, max) = (5.355, 5.651, 5.928), stdev = 0.287
  CI (99.9%): [0.414, 10.888] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.520 ops/ms
# Warmup Iteration   2: 4.144 ops/ms
# Warmup Iteration   3: 4.905 ops/ms
Iteration   1: 4.786 ops/ms
Iteration   2: 4.632 ops/ms
Iteration   3: 4.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.726 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (4.632, 4.726, 4.786), stdev = 0.083
  CI (99.9%): [3.218, 6.234] (assumes normal distribution)


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
# Warmup Iteration   1: 19.845 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.891 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.006 ±(99.9%) 0.013 ms/op
Iteration   1: 5.730 ±(99.9%) 0.012 ms/op
Iteration   2: 5.985 ±(99.9%) 0.012 ms/op
Iteration   3: 5.728 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.814 ±(99.9%) 2.698 ms/op [Average]
  (min, avg, max) = (5.728, 5.814, 5.985), stdev = 0.148
  CI (99.9%): [3.116, 8.513] (assumes normal distribution)


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
# Warmup Iteration   1: 17.175 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.251 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.010 ms/op
Iteration   1: 5.631 ±(99.9%) 0.012 ms/op
Iteration   2: 5.217 ±(99.9%) 0.005 ms/op
Iteration   3: 5.201 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.350 ±(99.9%) 4.446 ms/op [Average]
  (min, avg, max) = (5.201, 5.350, 5.631), stdev = 0.244
  CI (99.9%): [0.903, 9.796] (assumes normal distribution)


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
# Warmup Iteration   1: 17.219 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.398 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.127 ±(99.9%) 0.012 ms/op
Iteration   1: 5.692 ±(99.9%) 0.011 ms/op
Iteration   2: 5.215 ±(99.9%) 0.009 ms/op
Iteration   3: 5.118 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.342 ±(99.9%) 5.601 ms/op [Average]
  (min, avg, max) = (5.118, 5.342, 5.692), stdev = 0.307
  CI (99.9%): [≈ 0, 10.942] (assumes normal distribution)


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
# Warmup Iteration   1: 17.236 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 7.322 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.426 ±(99.9%) 0.009 ms/op
Iteration   1: 6.133 ±(99.9%) 0.013 ms/op
Iteration   2: 6.097 ±(99.9%) 0.009 ms/op
Iteration   3: 6.227 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.152 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (6.097, 6.152, 6.227), stdev = 0.067
  CI (99.9%): [4.932, 7.373] (assumes normal distribution)


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
# Warmup Iteration   1: 16.724 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.275 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.956 ±(99.9%) 0.027 ms/op
Iteration   1: 5.551 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.437 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   8.053 ms/op
                 createUser·p0.99:   11.731 ms/op
                 createUser·p0.999:  23.672 ms/op
                 createUser·p0.9999: 27.134 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   2: 5.579 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.277 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.988 ms/op
                 createUser·p0.95:   7.864 ms/op
                 createUser·p0.99:   12.010 ms/op
                 createUser·p0.999:  25.894 ms/op
                 createUser·p0.9999: 30.540 ms/op
                 createUser·p1.00:   32.113 ms/op

Iteration   3: 5.598 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.191 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   6.750 ms/op
                 createUser·p0.95:   7.741 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  21.568 ms/op
                 createUser·p0.9999: 31.935 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172106
  mean =      5.576 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 66274 
    [ 5.000,  7.500) = 94777 
    [ 7.500, 10.000) = 8146 
    [10.000, 12.500) = 1535 
    [12.500, 15.000) = 689 
    [15.000, 17.500) = 337 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      7.878 ms/op
     p(99.0000) =     11.469 ms/op
     p(99.9000) =     23.870 ms/op
     p(99.9900) =     31.221 ms/op
     p(99.9990) =     32.140 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.720 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.600 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.699 ±(99.9%) 0.022 ms/op
Iteration   1: 5.524 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.079 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.889 ms/op
                 existUser·p0.95:   7.856 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  24.547 ms/op
                 existUser·p0.9999: 27.270 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 5.549 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.798 ms/op
                 existUser·p0.50:   5.194 ms/op
                 existUser·p0.90:   6.988 ms/op
                 existUser·p0.95:   8.151 ms/op
                 existUser·p0.99:   11.105 ms/op
                 existUser·p0.999:  16.864 ms/op
                 existUser·p0.9999: 30.488 ms/op
                 existUser·p1.00:   31.785 ms/op

Iteration   3: 5.451 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.195 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.824 ms/op
                 existUser·p0.95:   7.974 ms/op
                 existUser·p0.99:   11.485 ms/op
                 existUser·p0.999:  28.410 ms/op
                 existUser·p0.9999: 31.892 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 174144
  mean =      5.508 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 73475 
    [ 5.000,  7.500) = 89037 
    [ 7.500, 10.000) = 8615 
    [10.000, 12.500) = 2012 
    [12.500, 15.000) = 491 
    [15.000, 17.500) = 232 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.889 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     11.043 ms/op
     p(99.9000) =     21.252 ms/op
     p(99.9900) =     31.515 ms/op
     p(99.9990) =     32.183 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.594 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.061 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.496 ±(99.9%) 0.019 ms/op
Iteration   1: 5.580 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.765 ms/op
                 getUser·p0.50:   5.128 ms/op
                 getUser·p0.90:   7.537 ms/op
                 getUser·p0.95:   8.421 ms/op
                 getUser·p0.99:   11.502 ms/op
                 getUser·p0.999:  18.481 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 5.441 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   6.504 ms/op
                 getUser·p0.95:   7.438 ms/op
                 getUser·p0.99:   10.977 ms/op
                 getUser·p0.999:  19.832 ms/op
                 getUser·p0.9999: 23.069 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 5.458 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.589 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   7.365 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  20.246 ms/op
                 getUser·p0.9999: 25.929 ms/op
                 getUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174705
  mean =      5.492 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 70654 
    [ 5.000,  7.500) = 92719 
    [ 7.500, 10.000) = 8830 
    [10.000, 12.500) = 1570 
    [12.500, 15.000) = 521 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     19.381 ms/op
     p(99.9900) =     25.380 ms/op
     p(99.9990) =     26.636 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


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
# Warmup Iteration   1: 20.423 ±(99.9%) 0.366 ms/op
# Warmup Iteration   2: 7.240 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.454 ±(99.9%) 0.024 ms/op
Iteration   1: 6.415 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   6.095 ms/op
                 listUser·p0.90:   7.823 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.239 ms/op
                 listUser·p0.999:  28.259 ms/op
                 listUser·p0.9999: 48.694 ms/op
                 listUser·p1.00:   49.218 ms/op

Iteration   2: 6.180 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   12.255 ms/op
                 listUser·p0.999:  28.467 ms/op
                 listUser·p0.9999: 33.394 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   3: 6.211 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   7.676 ms/op
                 listUser·p0.95:   8.978 ms/op
                 listUser·p0.99:   11.766 ms/op
                 listUser·p0.999:  21.038 ms/op
                 listUser·p0.9999: 24.163 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 153216
  mean =      6.267 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13749 
    [ 5.000, 10.000) = 135066 
    [10.000, 15.000) = 3670 
    [15.000, 20.000) = 416 
    [20.000, 25.000) = 135 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.668 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     26.182 ms/op
     p(99.9900) =     43.235 ms/op
     p(99.9990) =     49.218 ms/op
     p(99.9999) =     49.218 ms/op
    p(100.0000) =     49.218 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.695 ± 2.756  ops/ms
ClientPb.existUser                       thrpt       3   6.011 ± 2.334  ops/ms
ClientPb.getUser                         thrpt       3   5.651 ± 5.237  ops/ms
ClientPb.listUser                        thrpt       3   4.726 ± 1.508  ops/ms
ClientPb.createUser                       avgt       3   5.814 ± 2.698   ms/op
ClientPb.existUser                        avgt       3   5.350 ± 4.446   ms/op
ClientPb.getUser                          avgt       3   5.342 ± 5.601   ms/op
ClientPb.listUser                         avgt       3   6.152 ± 1.221   ms/op
ClientPb.createUser                     sample  172106   5.576 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.191           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.243           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.878           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.469           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.870           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.221           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.211           ms/op
ClientPb.existUser                      sample  174144   5.508 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.987           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.252           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.515           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.571           ms/op
ClientPb.getUser                        sample  174705   5.492 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.765           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.889           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.748           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.381           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.380           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.689           ms/op
ClientPb.listUser                       sample  153216   6.267 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.067           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.668           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.946           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.182           ms/op
ClientPb.listUser:listUser·p0.9999      sample          43.235           ms/op
ClientPb.listUser:listUser·p1.00        sample          49.218           ms/op
