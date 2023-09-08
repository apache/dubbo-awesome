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
# Warmup Iteration   1: 2.272 ops/ms
# Warmup Iteration   2: 5.677 ops/ms
# Warmup Iteration   3: 8.632 ops/ms
Iteration   1: 9.134 ops/ms
Iteration   2: 9.301 ops/ms
Iteration   3: 9.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.248 ±(99.9%) 1.796 ops/ms [Average]
  (min, avg, max) = (9.134, 9.248, 9.308), stdev = 0.098
  CI (99.9%): [7.452, 11.043] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 8.775 ops/ms
# Warmup Iteration   3: 9.057 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.574 ops/ms
Iteration   3: 9.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.532 ±(99.9%) 0.677 ops/ms [Average]
  (min, avg, max) = (9.506, 9.532, 9.574), stdev = 0.037
  CI (99.9%): [8.854, 10.209] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.974 ops/ms
# Warmup Iteration   2: 8.237 ops/ms
# Warmup Iteration   3: 8.894 ops/ms
Iteration   1: 9.211 ops/ms
Iteration   2: 9.024 ops/ms
Iteration   3: 8.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.075 ±(99.9%) 2.175 ops/ms [Average]
  (min, avg, max) = (8.989, 9.075, 9.211), stdev = 0.119
  CI (99.9%): [6.899, 11.250] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 2.879 ops/ms
# Warmup Iteration   2: 7.096 ops/ms
# Warmup Iteration   3: 7.627 ops/ms
Iteration   1: 7.692 ops/ms
Iteration   2: 7.857 ops/ms
Iteration   3: 8.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.860 ±(99.9%) 3.099 ops/ms [Average]
  (min, avg, max) = (7.692, 7.860, 8.032), stdev = 0.170
  CI (99.9%): [4.761, 10.959] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.486 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.680 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.007 ms/op
Iteration   1: 3.519 ±(99.9%) 0.007 ms/op
Iteration   2: 3.445 ±(99.9%) 0.008 ms/op
Iteration   3: 3.550 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.505 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.445, 3.505, 3.550), stdev = 0.054
  CI (99.9%): [2.516, 4.493] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.317 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.007 ms/op
Iteration   1: 3.362 ±(99.9%) 0.006 ms/op
Iteration   2: 3.344 ±(99.9%) 0.006 ms/op
Iteration   3: 3.370 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.359 ±(99.9%) 0.248 ms/op [Average]
  (min, avg, max) = (3.344, 3.359, 3.370), stdev = 0.014
  CI (99.9%): [3.110, 3.607] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 9.715 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.004 ms/op
Iteration   1: 3.411 ±(99.9%) 0.004 ms/op
Iteration   2: 3.413 ±(99.9%) 0.011 ms/op
Iteration   3: 3.447 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.424 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.411, 3.424, 3.447), stdev = 0.020
  CI (99.9%): [3.052, 3.795] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 11.513 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.006 ms/op
Iteration   1: 4.102 ±(99.9%) 0.007 ms/op
Iteration   2: 4.038 ±(99.9%) 0.009 ms/op
Iteration   3: 3.973 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.038 ±(99.9%) 1.183 ms/op [Average]
  (min, avg, max) = (3.973, 4.038, 4.102), stdev = 0.065
  CI (99.9%): [2.855, 5.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.267 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.548 ±(99.9%) 0.011 ms/op
Iteration   1: 3.390 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.329 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  21.684 ms/op
                 createUser·p0.9999: 24.187 ms/op
                 createUser·p1.00:   26.804 ms/op

Iteration   2: 3.343 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  22.032 ms/op
                 createUser·p0.9999: 26.468 ms/op
                 createUser·p1.00:   27.886 ms/op

Iteration   3: 3.524 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   6.812 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 26.603 ms/op
                 createUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280791
  mean =      3.417 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11049 
    [ 2.500,  5.000) = 261986 
    [ 5.000,  7.500) = 6274 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     18.593 ms/op
     p(99.9900) =     26.376 ms/op
     p(99.9990) =     27.132 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.845 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.731 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  14.036 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   2: 3.451 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  10.229 ms/op
                 existUser·p0.9999: 25.325 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 3.483 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  25.896 ms/op
                 existUser·p0.9999: 30.287 ms/op
                 existUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 281682
  mean =      3.406 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18847 
    [ 2.500,  5.000) = 254154 
    [ 5.000,  7.500) = 7286 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     12.621 ms/op
     p(99.9900) =     29.125 ms/op
     p(99.9990) =     32.178 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.643 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 4.248 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.011 ms/op
Iteration   1: 3.453 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.928 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 3.352 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.905 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  23.138 ms/op
                 getUser·p0.9999: 25.967 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.414 ms/op
                 getUser·p0.999:  11.387 ms/op
                 getUser·p0.9999: 27.200 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280818
  mean =      3.418 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5307 
    [ 2.500,  5.000) = 266439 
    [ 5.000,  7.500) = 7369 
    [ 7.500, 10.000) = 1012 
    [10.000, 12.500) = 369 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 92 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     14.312 ms/op
     p(99.9900) =     26.900 ms/op
     p(99.9990) =     28.509 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.604 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.485 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.014 ms/op
Iteration   1: 4.169 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  20.972 ms/op
                 listUser·p0.9999: 23.418 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.178 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.383 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   8.670 ms/op
                 listUser·p0.999:  16.237 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 19.138 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233039
  mean =      4.118 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 219433 
    [ 5.000,  7.500) = 9805 
    [ 7.500, 10.000) = 2457 
    [10.000, 12.500) = 778 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 200 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      8.369 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     22.688 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.248 ± 1.796  ops/ms
ClientPb.existUser                       thrpt       3   9.532 ± 0.677  ops/ms
ClientPb.getUser                         thrpt       3   9.075 ± 2.175  ops/ms
ClientPb.listUser                        thrpt       3   7.860 ± 3.099  ops/ms
ClientPb.createUser                       avgt       3   3.505 ± 0.989   ms/op
ClientPb.existUser                        avgt       3   3.359 ± 0.248   ms/op
ClientPb.getUser                          avgt       3   3.424 ± 0.372   ms/op
ClientPb.listUser                         avgt       3   4.038 ± 1.183   ms/op
ClientPb.createUser                     sample  280791   3.417 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.180           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.259           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.593           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  281682   3.406 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.409           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.751           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.621           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.125           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.309           ms/op
ClientPb.getUser                        sample  280818   3.418 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.521           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.312           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.900           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.852           ms/op
ClientPb.listUser                       sample  233039   4.118 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.383           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.369           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.105           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.688           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
