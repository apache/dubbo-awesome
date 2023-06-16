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
# Warmup Iteration   1: 1.105 ops/ms
# Warmup Iteration   2: 2.712 ops/ms
# Warmup Iteration   3: 5.784 ops/ms
Iteration   1: 5.791 ops/ms
Iteration   2: 6.114 ops/ms
Iteration   3: 6.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.018 ±(99.9%) 3.600 ops/ms [Average]
  (min, avg, max) = (5.791, 6.018, 6.149), stdev = 0.197
  CI (99.9%): [2.418, 9.618] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.751 ops/ms
# Warmup Iteration   2: 5.411 ops/ms
# Warmup Iteration   3: 6.158 ops/ms
Iteration   1: 6.773 ops/ms
Iteration   2: 6.588 ops/ms
Iteration   3: 6.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.618 ±(99.9%) 2.600 ops/ms [Average]
  (min, avg, max) = (6.493, 6.618, 6.773), stdev = 0.143
  CI (99.9%): [4.018, 9.218] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.634 ops/ms
# Warmup Iteration   2: 5.286 ops/ms
# Warmup Iteration   3: 6.135 ops/ms
Iteration   1: 5.962 ops/ms
Iteration   2: 6.066 ops/ms
Iteration   3: 6.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.052 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (5.962, 6.052, 6.129), stdev = 0.084
  CI (99.9%): [4.516, 7.588] (assumes normal distribution)


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
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 4.157 ops/ms
# Warmup Iteration   3: 5.216 ops/ms
Iteration   1: 5.069 ops/ms
Iteration   2: 5.181 ops/ms
Iteration   3: 5.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.201 ±(99.9%) 2.622 ops/ms [Average]
  (min, avg, max) = (5.069, 5.201, 5.354), stdev = 0.144
  CI (99.9%): [2.579, 7.824] (assumes normal distribution)


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
# Warmup Iteration   1: 17.147 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.001 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.569 ±(99.9%) 0.012 ms/op
Iteration   1: 5.257 ±(99.9%) 0.007 ms/op
Iteration   2: 5.203 ±(99.9%) 0.007 ms/op
Iteration   3: 5.233 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.231 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (5.203, 5.231, 5.257), stdev = 0.027
  CI (99.9%): [4.738, 5.724] (assumes normal distribution)


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
# Warmup Iteration   1: 16.542 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.308 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.172 ±(99.9%) 0.012 ms/op
Iteration   1: 5.170 ±(99.9%) 0.008 ms/op
Iteration   2: 5.022 ±(99.9%) 0.014 ms/op
Iteration   3: 4.947 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.047 ±(99.9%) 2.071 ms/op [Average]
  (min, avg, max) = (4.947, 5.047, 5.170), stdev = 0.114
  CI (99.9%): [2.976, 7.117] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.660 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.189 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.279 ±(99.9%) 0.009 ms/op
Iteration   1: 5.091 ±(99.9%) 0.017 ms/op
Iteration   2: 4.983 ±(99.9%) 0.010 ms/op
Iteration   3: 5.008 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.027 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (4.983, 5.027, 5.091), stdev = 0.056
  CI (99.9%): [3.997, 6.058] (assumes normal distribution)


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
# Warmup Iteration   1: 19.061 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 7.305 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.011 ms/op
Iteration   1: 6.218 ±(99.9%) 0.026 ms/op
Iteration   2: 6.254 ±(99.9%) 0.019 ms/op
Iteration   3: 5.956 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.142 ±(99.9%) 2.962 ms/op [Average]
  (min, avg, max) = (5.956, 6.142, 6.254), stdev = 0.162
  CI (99.9%): [3.180, 9.104] (assumes normal distribution)


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
# Warmup Iteration   1: 16.713 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.426 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.436 ±(99.9%) 0.023 ms/op
Iteration   1: 5.019 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.466 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   6.152 ms/op
                 createUser·p0.95:   7.070 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  23.921 ms/op
                 createUser·p0.9999: 28.246 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 5.117 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.095 ms/op
                 createUser·p0.50:   4.882 ms/op
                 createUser·p0.90:   6.095 ms/op
                 createUser·p0.95:   6.676 ms/op
                 createUser·p0.99:   8.815 ms/op
                 createUser·p0.999:  26.953 ms/op
                 createUser·p0.9999: 32.549 ms/op
                 createUser·p1.00:   34.537 ms/op

Iteration   3: 5.200 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   4.850 ms/op
                 createUser·p0.90:   6.406 ms/op
                 createUser·p0.95:   7.397 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  26.232 ms/op
                 createUser·p0.9999: 30.927 ms/op
                 createUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 187702
  mean =      5.111 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 114825 
    [ 5.000,  7.500) = 65953 
    [ 7.500, 10.000) = 5239 
    [10.000, 12.500) = 944 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 83 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.029 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     25.251 ms/op
     p(99.9900) =     30.915 ms/op
     p(99.9990) =     34.250 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


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
# Warmup Iteration   1: 16.817 ±(99.9%) 0.271 ms/op
# Warmup Iteration   2: 5.882 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.307 ±(99.9%) 0.020 ms/op
Iteration   1: 5.018 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.798 ms/op
                 existUser·p0.50:   4.694 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.250 ms/op
                 existUser·p0.99:   9.686 ms/op
                 existUser·p0.999:  21.794 ms/op
                 existUser·p0.9999: 28.627 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   2: 4.871 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.544 ms/op
                 existUser·p0.50:   4.710 ms/op
                 existUser·p0.90:   5.657 ms/op
                 existUser·p0.95:   6.742 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  14.247 ms/op
                 existUser·p0.9999: 27.160 ms/op
                 existUser·p1.00:   28.180 ms/op

Iteration   3: 4.929 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   5.898 ms/op
                 existUser·p0.95:   6.660 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  21.716 ms/op
                 existUser·p0.9999: 28.935 ms/op
                 existUser·p1.00:   29.622 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 194321
  mean =      4.938 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 143529 
    [ 5.000,  7.500) = 43793 
    [ 7.500, 10.000) = 5443 
    [10.000, 12.500) = 991 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     21.248 ms/op
     p(99.9900) =     28.560 ms/op
     p(99.9990) =     29.282 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 18.175 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 6.452 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.410 ±(99.9%) 0.019 ms/op
Iteration   1: 5.326 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.408 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   7.520 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  24.509 ms/op
                 getUser·p0.9999: 26.410 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   2: 5.321 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.232 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.865 ms/op
                 getUser·p0.95:   8.176 ms/op
                 getUser·p0.99:   10.912 ms/op
                 getUser·p0.999:  24.576 ms/op
                 getUser·p0.9999: 27.885 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 5.277 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   4.932 ms/op
                 getUser·p0.90:   6.431 ms/op
                 getUser·p0.95:   7.643 ms/op
                 getUser·p0.99:   11.370 ms/op
                 getUser·p0.999:  24.543 ms/op
                 getUser·p0.9999: 27.848 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180832
  mean =      5.308 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 97240 
    [ 5.000,  7.500) = 72472 
    [ 7.500, 10.000) = 8675 
    [10.000, 12.500) = 1416 
    [12.500, 15.000) = 576 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 135 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      4.940 ms/op
     p(90.0000) =      6.611 ms/op
     p(95.0000) =      7.848 ms/op
     p(99.0000) =     10.742 ms/op
     p(99.9000) =     24.576 ms/op
     p(99.9900) =     27.689 ms/op
     p(99.9990) =     29.802 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 19.852 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 7.624 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.374 ±(99.9%) 0.028 ms/op
Iteration   1: 6.326 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.834 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.848 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   12.111 ms/op
                 listUser·p0.999:  26.018 ms/op
                 listUser·p0.9999: 27.753 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 5.987 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.585 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  30.789 ms/op
                 listUser·p0.9999: 38.207 ms/op
                 listUser·p1.00:   39.453 ms/op

Iteration   3: 5.985 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.401 ms/op
                 listUser·p0.50:   5.718 ms/op
                 listUser·p0.90:   6.947 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   10.306 ms/op
                 listUser·p0.999:  19.923 ms/op
                 listUser·p0.9999: 28.690 ms/op
                 listUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157555
  mean =      6.095 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 10002 
    [ 5.000,  7.500) = 133394 
    [ 7.500, 10.000) = 10496 
    [10.000, 12.500) = 2702 
    [12.500, 15.000) = 437 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      5.726 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     37.157 ms/op
     p(99.9990) =     39.453 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.018 ± 3.600  ops/ms
ClientPb.existUser                       thrpt       3   6.618 ± 2.600  ops/ms
ClientPb.getUser                         thrpt       3   6.052 ± 1.536  ops/ms
ClientPb.listUser                        thrpt       3   5.201 ± 2.622  ops/ms
ClientPb.createUser                       avgt       3   5.231 ± 0.493   ms/op
ClientPb.existUser                        avgt       3   5.047 ± 2.071   ms/op
ClientPb.getUser                          avgt       3   5.027 ± 1.030   ms/op
ClientPb.listUser                         avgt       3   6.142 ± 2.962   ms/op
ClientPb.createUser                     sample  187702   5.111 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.765           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.210           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.029           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.617           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.251           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.915           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.537           ms/op
ClientPb.existUser                      sample  194321   4.938 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.686           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.923           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.939           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.503           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.248           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.560           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.622           ms/op
ClientPb.getUser                        sample  180832   5.308 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.940           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.848           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.742           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.576           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.689           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.147           ms/op
ClientPb.listUser                       sample  157555   6.095 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.401           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.567           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.444           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.453           ms/op
