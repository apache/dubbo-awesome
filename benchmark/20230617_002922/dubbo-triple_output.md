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
# Warmup Iteration   1: 2.046 ops/ms
# Warmup Iteration   2: 4.669 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.991 ops/ms
Iteration   2: 9.192 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.117 ±(99.9%) 2.008 ops/ms [Average]
  (min, avg, max) = (8.991, 9.117, 9.192), stdev = 0.110
  CI (99.9%): [7.109, 11.125] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ops/ms
# Warmup Iteration   2: 8.686 ops/ms
# Warmup Iteration   3: 8.984 ops/ms
Iteration   1: 9.628 ops/ms
Iteration   2: 9.564 ops/ms
Iteration   3: 9.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.543 ±(99.9%) 1.772 ops/ms [Average]
  (min, avg, max) = (9.437, 9.543, 9.628), stdev = 0.097
  CI (99.9%): [7.771, 11.315] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.646 ops/ms
# Warmup Iteration   2: 8.093 ops/ms
# Warmup Iteration   3: 8.917 ops/ms
Iteration   1: 9.318 ops/ms
Iteration   2: 9.174 ops/ms
Iteration   3: 9.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.192 ±(99.9%) 2.155 ops/ms [Average]
  (min, avg, max) = (9.084, 9.192, 9.318), stdev = 0.118
  CI (99.9%): [7.037, 11.347] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.509 ops/ms
# Warmup Iteration   2: 7.044 ops/ms
# Warmup Iteration   3: 7.903 ops/ms
Iteration   1: 7.718 ops/ms
Iteration   2: 8.101 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.956 ±(99.9%) 3.789 ops/ms [Average]
  (min, avg, max) = (7.718, 7.956, 8.101), stdev = 0.208
  CI (99.9%): [4.167, 11.745] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.620 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.004 ms/op
Iteration   1: 3.489 ±(99.9%) 0.008 ms/op
Iteration   2: 3.506 ±(99.9%) 0.007 ms/op
Iteration   3: 3.513 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.503 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (3.489, 3.503, 3.513), stdev = 0.012
  CI (99.9%): [3.284, 3.721] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 10.483 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.004 ms/op
Iteration   1: 3.257 ±(99.9%) 0.010 ms/op
Iteration   2: 3.284 ±(99.9%) 0.007 ms/op
Iteration   3: 3.314 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.285 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.257, 3.285, 3.314), stdev = 0.028
  CI (99.9%): [2.766, 3.804] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.476 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.620 ±(99.9%) 0.005 ms/op
Iteration   1: 3.512 ±(99.9%) 0.006 ms/op
Iteration   2: 3.498 ±(99.9%) 0.008 ms/op
Iteration   3: 3.586 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.532 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (3.498, 3.532, 3.586), stdev = 0.047
  CI (99.9%): [2.668, 4.396] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.731 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.530 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.006 ms/op
Iteration   1: 4.012 ±(99.9%) 0.010 ms/op
Iteration   2: 4.048 ±(99.9%) 0.010 ms/op
Iteration   3: 3.975 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.012 ±(99.9%) 0.670 ms/op [Average]
  (min, avg, max) = (3.975, 4.012, 4.048), stdev = 0.037
  CI (99.9%): [3.342, 4.681] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.106 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.382 ±(99.9%) 0.010 ms/op
Iteration   1: 3.507 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  21.263 ms/op
                 createUser·p0.9999: 25.162 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.465 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.216 ms/op
                 createUser·p0.99:   6.717 ms/op
                 createUser·p0.999:  23.089 ms/op
                 createUser·p0.9999: 34.313 ms/op
                 createUser·p1.00:   34.800 ms/op

Iteration   3: 3.340 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   5.766 ms/op
                 createUser·p0.999:  19.057 ms/op
                 createUser·p0.9999: 29.571 ms/op
                 createUser·p1.00:   31.523 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278933
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12961 
    [ 2.500,  5.000) = 257553 
    [ 5.000,  7.500) = 7213 
    [ 7.500, 10.000) = 686 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     21.015 ms/op
     p(99.9900) =     32.775 ms/op
     p(99.9990) =     34.748 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.740 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.573 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
Iteration   1: 3.375 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.329 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.570 ms/op
                 existUser·p0.999:  19.941 ms/op
                 existUser·p0.9999: 23.741 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.370 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  23.178 ms/op
                 existUser·p0.9999: 26.018 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.170 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  9.791 ms/op
                 existUser·p0.9999: 27.765 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285244
  mean =      3.365 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15003 
    [ 2.500,  5.000) = 262378 
    [ 5.000,  7.500) = 6636 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 88 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     18.768 ms/op
     p(99.9900) =     26.801 ms/op
     p(99.9990) =     28.579 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.134 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
Iteration   1: 3.596 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  20.055 ms/op
                 getUser·p0.9999: 23.963 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.504 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.015 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   7.520 ms/op
                 getUser·p0.999:  23.584 ms/op
                 getUser·p0.9999: 44.696 ms/op
                 getUser·p1.00:   45.154 ms/op

Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  21.148 ms/op
                 getUser·p0.9999: 29.262 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274561
  mean =      3.495 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262818 
    [ 5.000, 10.000) = 10842 
    [10.000, 15.000) = 512 
    [15.000, 20.000) = 96 
    [20.000, 25.000) = 175 
    [25.000, 30.000) = 84 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     40.352 ms/op
     p(99.9990) =     44.974 ms/op
     p(99.9999) =     45.154 ms/op
    p(100.0000) =     45.154 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 12.726 ±(99.9%) 0.172 ms/op
# Warmup Iteration   2: 4.879 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.262 ±(99.9%) 0.015 ms/op
Iteration   1: 4.103 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  23.105 ms/op
                 listUser·p0.9999: 29.093 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.630 ms/op
                 listUser·p0.999:  16.778 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   3: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.134 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 20.483 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235888
  mean =      4.066 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24 
    [ 2.500,  5.000) = 226483 
    [ 5.000,  7.500) = 6637 
    [ 7.500, 10.000) = 1744 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.019 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     18.536 ms/op
     p(99.9900) =     27.419 ms/op
     p(99.9990) =     29.671 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.117 ± 2.008  ops/ms
ClientPb.existUser                       thrpt       3   9.543 ± 1.772  ops/ms
ClientPb.getUser                         thrpt       3   9.192 ± 2.155  ops/ms
ClientPb.listUser                        thrpt       3   7.956 ± 3.789  ops/ms
ClientPb.createUser                       avgt       3   3.503 ± 0.219   ms/op
ClientPb.existUser                        avgt       3   3.285 ± 0.519   ms/op
ClientPb.getUser                          avgt       3   3.532 ± 0.864   ms/op
ClientPb.listUser                         avgt       3   4.012 ± 0.670   ms/op
ClientPb.createUser                     sample  278933   3.436 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.015           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.775           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.800           ms/op
ClientPb.existUser                      sample  285244   3.365 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.329           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.062           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.768           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.801           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.705           ms/op
ClientPb.getUser                        sample  274561   3.495 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.370           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.301           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.578           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.352           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.154           ms/op
ClientPb.listUser                       sample  235888   4.066 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.019           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.774           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.536           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.419           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
