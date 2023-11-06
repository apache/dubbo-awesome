# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.219 ops/ms
# Warmup Iteration   2: 2.928 ops/ms
# Warmup Iteration   3: 6.063 ops/ms
Iteration   1: 5.867 ops/ms
Iteration   2: 5.660 ops/ms
Iteration   3: 5.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.834 ±(99.9%) 2.918 ops/ms [Average]
  (min, avg, max) = (5.660, 5.834, 5.974), stdev = 0.160
  CI (99.9%): [2.916, 8.751] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.858 ops/ms
# Warmup Iteration   2: 5.231 ops/ms
# Warmup Iteration   3: 6.480 ops/ms
Iteration   1: 6.440 ops/ms
Iteration   2: 6.446 ops/ms
Iteration   3: 6.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.495 ±(99.9%) 1.630 ops/ms [Average]
  (min, avg, max) = (6.440, 6.495, 6.598), stdev = 0.089
  CI (99.9%): [4.865, 8.124] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.757 ops/ms
# Warmup Iteration   2: 4.939 ops/ms
# Warmup Iteration   3: 6.051 ops/ms
Iteration   1: 6.033 ops/ms
Iteration   2: 6.179 ops/ms
Iteration   3: 6.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.099 ±(99.9%) 1.350 ops/ms [Average]
  (min, avg, max) = (6.033, 6.099, 6.179), stdev = 0.074
  CI (99.9%): [4.749, 7.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.798 ops/ms
# Warmup Iteration   2: 4.698 ops/ms
# Warmup Iteration   3: 5.503 ops/ms
Iteration   1: 5.326 ops/ms
Iteration   2: 5.420 ops/ms
Iteration   3: 5.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.390 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (5.326, 5.390, 5.423), stdev = 0.055
  CI (99.9%): [4.383, 6.397] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.698 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.469 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.591 ±(99.9%) 0.014 ms/op
Iteration   1: 5.676 ±(99.9%) 0.013 ms/op
Iteration   2: 5.957 ±(99.9%) 0.010 ms/op
Iteration   3: 5.353 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.662 ±(99.9%) 5.512 ms/op [Average]
  (min, avg, max) = (5.353, 5.662, 5.957), stdev = 0.302
  CI (99.9%): [0.150, 11.174] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.532 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 6.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.412 ±(99.9%) 0.009 ms/op
Iteration   1: 5.142 ±(99.9%) 0.016 ms/op
Iteration   2: 4.954 ±(99.9%) 0.017 ms/op
Iteration   3: 5.138 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.078 ±(99.9%) 1.953 ms/op [Average]
  (min, avg, max) = (4.954, 5.078, 5.142), stdev = 0.107
  CI (99.9%): [3.125, 7.030] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 18.087 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.829 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.370 ±(99.9%) 0.014 ms/op
Iteration   1: 5.527 ±(99.9%) 0.009 ms/op
Iteration   2: 5.345 ±(99.9%) 0.009 ms/op
Iteration   3: 5.258 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.377 ±(99.9%) 2.500 ms/op [Average]
  (min, avg, max) = (5.258, 5.377, 5.527), stdev = 0.137
  CI (99.9%): [2.876, 7.877] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 19.840 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.106 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.300 ±(99.9%) 0.012 ms/op
Iteration   1: 6.451 ±(99.9%) 0.009 ms/op
Iteration   2: 6.272 ±(99.9%) 0.013 ms/op
Iteration   3: 6.258 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.327 ±(99.9%) 1.963 ms/op [Average]
  (min, avg, max) = (6.258, 6.327, 6.451), stdev = 0.108
  CI (99.9%): [4.364, 8.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.313 ±(99.9%) 0.279 ms/op
# Warmup Iteration   2: 7.130 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.906 ±(99.9%) 0.026 ms/op
Iteration   1: 5.421 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.660 ms/op
                 createUser·p0.99:   10.260 ms/op
                 createUser·p0.999:  23.857 ms/op
                 createUser·p0.9999: 28.322 ms/op
                 createUser·p1.00:   32.145 ms/op

Iteration   2: 5.271 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.257 ms/op
                 createUser·p0.50:   4.940 ms/op
                 createUser·p0.90:   6.504 ms/op
                 createUser·p0.95:   7.168 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  25.002 ms/op
                 createUser·p0.9999: 33.882 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   3: 5.413 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.408 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.529 ms/op
                 createUser·p0.95:   7.266 ms/op
                 createUser·p0.99:   9.896 ms/op
                 createUser·p0.999:  27.590 ms/op
                 createUser·p0.9999: 32.607 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178626
  mean =      5.367 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 83964 
    [ 5.000,  7.500) = 86424 
    [ 7.500, 10.000) = 6312 
    [10.000, 12.500) = 1151 
    [12.500, 15.000) = 377 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.586 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =     10.154 ms/op
     p(99.9000) =     24.863 ms/op
     p(99.9900) =     33.526 ms/op
     p(99.9990) =     34.252 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 15.238 ±(99.9%) 0.236 ms/op
# Warmup Iteration   2: 5.733 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.018 ms/op
Iteration   1: 5.157 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.249 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   6.349 ms/op
                 existUser·p0.95:   6.988 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  23.262 ms/op
                 existUser·p0.9999: 27.365 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   2: 5.318 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.208 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.365 ms/op
                 existUser·p0.95:   7.193 ms/op
                 existUser·p0.99:   11.158 ms/op
                 existUser·p0.999:  24.476 ms/op
                 existUser·p0.9999: 27.132 ms/op
                 existUser·p1.00:   28.213 ms/op

Iteration   3: 5.114 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.257 ms/op
                 existUser·p0.50:   4.874 ms/op
                 existUser·p0.90:   6.152 ms/op
                 existUser·p0.95:   6.849 ms/op
                 existUser·p0.99:   9.343 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 33.948 ms/op
                 existUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 184744
  mean =      5.195 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 100135 
    [ 5.000,  7.500) = 77815 
    [ 7.500, 10.000) = 5160 
    [10.000, 12.500) = 859 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      4.923 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.004 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     31.255 ms/op
     p(99.9990) =     34.472 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.670 ±(99.9%) 0.268 ms/op
# Warmup Iteration   2: 6.368 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.627 ±(99.9%) 0.018 ms/op
Iteration   1: 5.480 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.421 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.578 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  22.770 ms/op
                 getUser·p0.9999: 26.301 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   2: 5.377 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.830 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   6.390 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   10.453 ms/op
                 getUser·p0.999:  24.855 ms/op
                 getUser·p0.9999: 28.606 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 5.294 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   5.030 ms/op
                 getUser·p0.90:   6.283 ms/op
                 getUser·p0.95:   7.225 ms/op
                 getUser·p0.99:   9.912 ms/op
                 getUser·p0.999:  23.875 ms/op
                 getUser·p0.9999: 29.288 ms/op
                 getUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 178303
  mean =      5.382 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 78165 
    [ 5.000,  7.500) = 91401 
    [ 7.500, 10.000) = 6546 
    [10.000, 12.500) = 1307 
    [12.500, 15.000) = 477 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 102 

  Percentiles, ms/op:
      p(0.0000) =      1.784 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.447 ms/op
     p(99.0000) =     10.534 ms/op
     p(99.9000) =     23.583 ms/op
     p(99.9900) =     28.252 ms/op
     p(99.9990) =     29.531 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.742 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 7.544 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 6.430 ±(99.9%) 0.023 ms/op
Iteration   1: 6.278 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.376 ms/op
                 listUser·p0.50:   6.013 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.315 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  25.503 ms/op
                 listUser·p0.9999: 28.034 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   2: 6.310 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   5.947 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   12.812 ms/op
                 listUser·p0.999:  28.574 ms/op
                 listUser·p0.9999: 33.686 ms/op
                 listUser·p1.00:   34.144 ms/op

Iteration   3: 6.264 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.977 ms/op
                 listUser·p0.999:  22.610 ms/op
                 listUser·p0.9999: 31.086 ms/op
                 listUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 152683
  mean =      6.284 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 8804 
    [ 5.000,  7.500) = 129201 
    [ 7.500, 10.000) = 10886 
    [10.000, 12.500) = 2415 
    [12.500, 15.000) = 742 
    [15.000, 17.500) = 241 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.091 ms/op
     p(50.0000) =      5.980 ms/op
     p(90.0000) =      7.455 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     26.083 ms/op
     p(99.9900) =     32.200 ms/op
     p(99.9990) =     34.075 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.834 ± 2.918  ops/ms
ClientPb.existUser                       thrpt       3   6.495 ± 1.630  ops/ms
ClientPb.getUser                         thrpt       3   6.099 ± 1.350  ops/ms
ClientPb.listUser                        thrpt       3   5.390 ± 1.007  ops/ms
ClientPb.createUser                       avgt       3   5.662 ± 5.512   ms/op
ClientPb.existUser                        avgt       3   5.078 ± 1.953   ms/op
ClientPb.getUser                          avgt       3   5.377 ± 2.500   ms/op
ClientPb.listUser                         avgt       3   6.327 ± 1.963   ms/op
ClientPb.createUser                     sample  178626   5.367 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.381           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.154           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.863           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.526           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  184744   5.195 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.291           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.004           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.650           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.472           ms/op
ClientPb.getUser                        sample  178303   5.382 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.784           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.095           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.447           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.534           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.583           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.252           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.557           ms/op
ClientPb.listUser                       sample  152683   6.284 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.091           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.980           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.190           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.083           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.144           ms/op
