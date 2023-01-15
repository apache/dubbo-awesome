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
# Warmup Iteration   1: 0.963 ops/ms
# Warmup Iteration   2: 2.258 ops/ms
# Warmup Iteration   3: 5.171 ops/ms
Iteration   1: 5.642 ops/ms
Iteration   2: 6.027 ops/ms
Iteration   3: 5.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.811 ±(99.9%) 3.588 ops/ms [Average]
  (min, avg, max) = (5.642, 5.811, 6.027), stdev = 0.197
  CI (99.9%): [2.223, 9.400] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.704 ops/ms
# Warmup Iteration   2: 4.946 ops/ms
# Warmup Iteration   3: 6.028 ops/ms
Iteration   1: 5.812 ops/ms
Iteration   2: 5.855 ops/ms
Iteration   3: 6.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.958 ±(99.9%) 3.946 ops/ms [Average]
  (min, avg, max) = (5.812, 5.958, 6.206), stdev = 0.216
  CI (99.9%): [2.012, 9.904] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.624 ops/ms
# Warmup Iteration   2: 4.804 ops/ms
# Warmup Iteration   3: 5.973 ops/ms
Iteration   1: 5.988 ops/ms
Iteration   2: 6.078 ops/ms
Iteration   3: 6.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.102 ±(99.9%) 2.334 ops/ms [Average]
  (min, avg, max) = (5.988, 6.102, 6.241), stdev = 0.128
  CI (99.9%): [3.768, 8.436] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.636 ops/ms
# Warmup Iteration   2: 3.879 ops/ms
# Warmup Iteration   3: 5.207 ops/ms
Iteration   1: 4.655 ops/ms
Iteration   2: 4.882 ops/ms
Iteration   3: 5.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.888 ±(99.9%) 4.306 ops/ms [Average]
  (min, avg, max) = (4.655, 4.888, 5.127), stdev = 0.236
  CI (99.9%): [0.582, 9.194] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.270 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 6.543 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.537 ±(99.9%) 0.008 ms/op
Iteration   1: 5.337 ±(99.9%) 0.012 ms/op
Iteration   2: 5.117 ±(99.9%) 0.015 ms/op
Iteration   3: 5.061 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.172 ±(99.9%) 2.661 ms/op [Average]
  (min, avg, max) = (5.061, 5.172, 5.337), stdev = 0.146
  CI (99.9%): [2.511, 7.833] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.444 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.838 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.258 ±(99.9%) 0.009 ms/op
Iteration   1: 5.079 ±(99.9%) 0.010 ms/op
Iteration   2: 5.125 ±(99.9%) 0.009 ms/op
Iteration   3: 5.019 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.074 ±(99.9%) 0.965 ms/op [Average]
  (min, avg, max) = (5.019, 5.074, 5.125), stdev = 0.053
  CI (99.9%): [4.109, 6.039] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 17.831 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.578 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.332 ±(99.9%) 0.010 ms/op
Iteration   1: 5.450 ±(99.9%) 0.013 ms/op
Iteration   2: 5.311 ±(99.9%) 0.013 ms/op
Iteration   3: 5.268 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.343 ±(99.9%) 1.740 ms/op [Average]
  (min, avg, max) = (5.268, 5.343, 5.450), stdev = 0.095
  CI (99.9%): [3.603, 7.083] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.947 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 7.611 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.553 ±(99.9%) 0.013 ms/op
Iteration   1: 6.360 ±(99.9%) 0.013 ms/op
Iteration   2: 6.131 ±(99.9%) 0.015 ms/op
Iteration   3: 6.158 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.216 ±(99.9%) 2.283 ms/op [Average]
  (min, avg, max) = (6.131, 6.216, 6.360), stdev = 0.125
  CI (99.9%): [3.934, 8.499] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.932 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.060 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.069 ±(99.9%) 0.031 ms/op
Iteration   1: 5.574 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.347 ms/op
                 createUser·p0.50:   5.292 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   11.076 ms/op
                 createUser·p0.999:  23.176 ms/op
                 createUser·p0.9999: 26.954 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   2: 5.526 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.310 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.971 ms/op
                 createUser·p0.95:   8.012 ms/op
                 createUser·p0.99:   10.598 ms/op
                 createUser·p0.999:  17.668 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 5.782 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.679 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.619 ms/op
                 createUser·p0.95:   8.749 ms/op
                 createUser·p0.99:   11.747 ms/op
                 createUser·p0.999:  33.592 ms/op
                 createUser·p0.9999: 40.563 ms/op
                 createUser·p1.00:   43.647 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170440
  mean =      5.625 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64570 
    [ 5.000, 10.000) = 102659 
    [10.000, 15.000) = 2781 
    [15.000, 20.000) = 203 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 80 
    [30.000, 35.000) = 36 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.310 ms/op
     p(50.0000) =      5.259 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.282 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     24.598 ms/op
     p(99.9900) =     40.236 ms/op
     p(99.9990) =     43.047 ms/op
     p(99.9999) =     43.647 ms/op
    p(100.0000) =     43.647 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.382 ±(99.9%) 0.267 ms/op
# Warmup Iteration   2: 6.936 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.021 ms/op
Iteration   1: 5.698 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.429 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   7.709 ms/op
                 existUser·p0.95:   9.208 ms/op
                 existUser·p0.99:   11.960 ms/op
                 existUser·p0.999:  16.605 ms/op
                 existUser·p0.9999: 32.103 ms/op
                 existUser·p1.00:   33.325 ms/op

Iteration   2: 5.320 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.786 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.586 ms/op
                 existUser·p0.95:   7.905 ms/op
                 existUser·p0.99:   11.711 ms/op
                 existUser·p0.999:  26.752 ms/op
                 existUser·p0.9999: 35.254 ms/op
                 existUser·p1.00:   35.586 ms/op

Iteration   3: 5.299 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.437 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.610 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  27.511 ms/op
                 existUser·p0.9999: 31.717 ms/op
                 existUser·p1.00:   33.325 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 176647
  mean =      5.433 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 84864 
    [ 5.000,  7.500) = 78631 
    [ 7.500, 10.000) = 9369 
    [10.000, 12.500) = 2584 
    [12.500, 15.000) = 746 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 83 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.786 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     11.633 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     32.670 ms/op
     p(99.9990) =     35.536 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


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
# Warmup Iteration   1: 18.401 ±(99.9%) 0.292 ms/op
# Warmup Iteration   2: 6.406 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.654 ±(99.9%) 0.021 ms/op
Iteration   1: 5.634 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.269 ms/op
                 getUser·p0.50:   5.218 ms/op
                 getUser·p0.90:   7.053 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   12.042 ms/op
                 getUser·p0.999:  26.256 ms/op
                 getUser·p0.9999: 45.023 ms/op
                 getUser·p1.00:   47.448 ms/op

Iteration   2: 5.539 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   8.339 ms/op
                 getUser·p0.99:   12.190 ms/op
                 getUser·p0.999:  17.760 ms/op
                 getUser·p0.9999: 28.836 ms/op
                 getUser·p1.00:   29.426 ms/op

Iteration   3: 5.523 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.186 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   11.301 ms/op
                 getUser·p0.999:  26.547 ms/op
                 getUser·p0.9999: 36.350 ms/op
                 getUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 172385
  mean =      5.565 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 67278 
    [ 5.000, 10.000) = 101387 
    [10.000, 15.000) = 3054 
    [15.000, 20.000) = 436 
    [20.000, 25.000) = 59 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.688 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.865 ms/op
     p(95.0000) =      8.225 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     41.436 ms/op
     p(99.9990) =     45.977 ms/op
     p(99.9999) =     47.448 ms/op
    p(100.0000) =     47.448 ms/op


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
# Warmup Iteration   1: 20.003 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 7.712 ±(99.9%) 0.051 ms/op
# Warmup Iteration   3: 6.543 ±(99.9%) 0.028 ms/op
Iteration   1: 6.216 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   0.528 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   8.118 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   12.780 ms/op
                 listUser·p0.999:  25.133 ms/op
                 listUser·p0.9999: 27.987 ms/op
                 listUser·p1.00:   29.622 ms/op

Iteration   2: 6.455 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.080 ms/op
                 listUser·p0.50:   5.972 ms/op
                 listUser·p0.90:   8.220 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  29.555 ms/op
                 listUser·p0.9999: 42.542 ms/op
                 listUser·p1.00:   42.861 ms/op

Iteration   3: 6.638 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.920 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.684 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   12.845 ms/op
                 listUser·p0.999:  26.472 ms/op
                 listUser·p0.9999: 35.139 ms/op
                 listUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 149183
  mean =      6.432 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11667 
    [ 5.000, 10.000) = 131727 
    [10.000, 15.000) = 5056 
    [15.000, 20.000) = 383 
    [20.000, 25.000) = 136 
    [25.000, 30.000) = 137 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 7 
    [40.000, 45.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      5.947 ms/op
     p(90.0000) =      8.372 ms/op
     p(95.0000) =      9.585 ms/op
     p(99.0000) =     12.796 ms/op
     p(99.9000) =     26.676 ms/op
     p(99.9900) =     41.752 ms/op
     p(99.9990) =     42.828 ms/op
     p(99.9999) =     42.861 ms/op
    p(100.0000) =     42.861 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.811 ± 3.588  ops/ms
ClientPb.existUser                       thrpt       3   5.958 ± 3.946  ops/ms
ClientPb.getUser                         thrpt       3   6.102 ± 2.334  ops/ms
ClientPb.listUser                        thrpt       3   4.888 ± 4.306  ops/ms
ClientPb.createUser                       avgt       3   5.172 ± 2.661   ms/op
ClientPb.existUser                        avgt       3   5.074 ± 0.965   ms/op
ClientPb.getUser                          avgt       3   5.343 ± 1.740   ms/op
ClientPb.listUser                         avgt       3   6.216 ± 2.283   ms/op
ClientPb.createUser                     sample  170440   5.625 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.310           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.259           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.176           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.282           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.125           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.598           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.236           ms/op
ClientPb.createUser:createUser·p1.00    sample          43.647           ms/op
ClientPb.existUser                      sample  176647   5.433 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.786           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.996           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.290           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.633           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.429           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.670           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.586           ms/op
ClientPb.getUser                        sample  172385   5.565 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.688           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.194           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.865           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.225           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.747           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.904           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.436           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.448           ms/op
ClientPb.listUser                       sample  149183   6.432 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.947           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.585           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.796           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.676           ms/op
ClientPb.listUser:listUser·p0.9999      sample          41.752           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.861           ms/op
