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
# Warmup Iteration   1: 0.886 ops/ms
# Warmup Iteration   2: 2.035 ops/ms
# Warmup Iteration   3: 4.800 ops/ms
Iteration   1: 5.131 ops/ms
Iteration   2: 5.530 ops/ms
Iteration   3: 5.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.375 ±(99.9%) 3.897 ops/ms [Average]
  (min, avg, max) = (5.131, 5.375, 5.530), stdev = 0.214
  CI (99.9%): [1.478, 9.272] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.561 ops/ms
# Warmup Iteration   2: 4.528 ops/ms
# Warmup Iteration   3: 5.427 ops/ms
Iteration   1: 5.829 ops/ms
Iteration   2: 5.777 ops/ms
Iteration   3: 5.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.856 ±(99.9%) 1.753 ops/ms [Average]
  (min, avg, max) = (5.777, 5.856, 5.963), stdev = 0.096
  CI (99.9%): [4.104, 7.609] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.502 ops/ms
# Warmup Iteration   2: 4.180 ops/ms
# Warmup Iteration   3: 5.403 ops/ms
Iteration   1: 5.593 ops/ms
Iteration   2: 5.473 ops/ms
Iteration   3: 5.471 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.512 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (5.471, 5.512, 5.593), stdev = 0.070
  CI (99.9%): [4.240, 6.784] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.516 ops/ms
# Warmup Iteration   2: 3.632 ops/ms
# Warmup Iteration   3: 4.304 ops/ms
Iteration   1: 4.369 ops/ms
Iteration   2: 4.417 ops/ms
Iteration   3: 4.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.431 ±(99.9%) 1.262 ops/ms [Average]
  (min, avg, max) = (4.369, 4.431, 4.505), stdev = 0.069
  CI (99.9%): [3.169, 5.692] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.909 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.405 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.201 ±(99.9%) 0.008 ms/op
Iteration   1: 5.955 ±(99.9%) 0.014 ms/op
Iteration   2: 5.789 ±(99.9%) 0.014 ms/op
Iteration   3: 5.925 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.889 ±(99.9%) 1.614 ms/op [Average]
  (min, avg, max) = (5.789, 5.889, 5.955), stdev = 0.088
  CI (99.9%): [4.275, 7.503] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.967 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 7.016 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.008 ms/op
Iteration   1: 5.465 ±(99.9%) 0.011 ms/op
Iteration   2: 5.372 ±(99.9%) 0.011 ms/op
Iteration   3: 5.476 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.438 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (5.372, 5.438, 5.476), stdev = 0.057
  CI (99.9%): [4.401, 6.475] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 20.667 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 7.922 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.263 ±(99.9%) 0.008 ms/op
Iteration   1: 5.989 ±(99.9%) 0.007 ms/op
Iteration   2: 5.799 ±(99.9%) 0.011 ms/op
Iteration   3: 5.766 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.852 ±(99.9%) 2.198 ms/op [Average]
  (min, avg, max) = (5.766, 5.852, 5.989), stdev = 0.120
  CI (99.9%): [3.654, 8.049] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 23.041 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 8.331 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.993 ±(99.9%) 0.011 ms/op
Iteration   1: 6.735 ±(99.9%) 0.019 ms/op
Iteration   2: 6.881 ±(99.9%) 0.009 ms/op
Iteration   3: 6.790 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.802 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (6.735, 6.802, 6.881), stdev = 0.074
  CI (99.9%): [5.457, 8.148] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 21.063 ±(99.9%) 0.349 ms/op
# Warmup Iteration   2: 7.383 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.227 ±(99.9%) 0.031 ms/op
Iteration   1: 5.931 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.515 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.365 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   11.633 ms/op
                 createUser·p0.999:  25.595 ms/op
                 createUser·p0.9999: 29.540 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   2: 5.761 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   5.439 ms/op
                 createUser·p0.90:   7.029 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   11.141 ms/op
                 createUser·p0.999:  29.128 ms/op
                 createUser·p0.9999: 38.790 ms/op
                 createUser·p1.00:   39.322 ms/op

Iteration   3: 5.814 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   12.354 ms/op
                 createUser·p0.999:  29.106 ms/op
                 createUser·p0.9999: 32.260 ms/op
                 createUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164421
  mean =      5.834 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 36743 
    [ 5.000,  7.500) = 115102 
    [ 7.500, 10.000) = 9171 
    [10.000, 12.500) = 2213 
    [12.500, 15.000) = 637 
    [15.000, 17.500) = 217 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.192 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     27.460 ms/op
     p(99.9900) =     36.999 ms/op
     p(99.9990) =     39.195 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 18.648 ±(99.9%) 0.358 ms/op
# Warmup Iteration   2: 6.884 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.663 ±(99.9%) 0.021 ms/op
Iteration   1: 5.581 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.401 ms/op
                 existUser·p0.50:   5.259 ms/op
                 existUser·p0.90:   6.816 ms/op
                 existUser·p0.95:   7.873 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  28.417 ms/op
                 existUser·p0.9999: 46.274 ms/op
                 existUser·p1.00:   47.383 ms/op

Iteration   2: 5.626 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   6.939 ms/op
                 existUser·p0.95:   8.086 ms/op
                 existUser·p0.99:   11.289 ms/op
                 existUser·p0.999:  29.102 ms/op
                 existUser·p0.9999: 35.082 ms/op
                 existUser·p1.00:   36.110 ms/op

Iteration   3: 5.490 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.441 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   6.881 ms/op
                 existUser·p0.95:   8.151 ms/op
                 existUser·p0.99:   11.321 ms/op
                 existUser·p0.999:  22.813 ms/op
                 existUser·p0.9999: 32.965 ms/op
                 existUser·p1.00:   33.456 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 172252
  mean =      5.565 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 61137 
    [ 5.000, 10.000) = 108163 
    [10.000, 15.000) = 2476 
    [15.000, 20.000) = 204 
    [20.000, 25.000) = 61 
    [25.000, 30.000) = 76 
    [30.000, 35.000) = 86 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.401 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     11.158 ms/op
     p(99.9000) =     27.886 ms/op
     p(99.9900) =     41.091 ms/op
     p(99.9990) =     47.335 ms/op
     p(99.9999) =     47.383 ms/op
    p(100.0000) =     47.383 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.709 ±(99.9%) 0.326 ms/op
# Warmup Iteration   2: 7.153 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.903 ±(99.9%) 0.028 ms/op
Iteration   1: 5.810 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.915 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   13.206 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 30.407 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   2: 5.770 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   5.439 ms/op
                 getUser·p0.90:   7.078 ms/op
                 getUser·p0.95:   8.211 ms/op
                 getUser·p0.99:   11.108 ms/op
                 getUser·p0.999:  30.087 ms/op
                 getUser·p0.9999: 36.856 ms/op
                 getUser·p1.00:   37.290 ms/op

Iteration   3: 5.784 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.763 ms/op
                 getUser·p0.50:   5.472 ms/op
                 getUser·p0.90:   7.062 ms/op
                 getUser·p0.95:   8.033 ms/op
                 getUser·p0.99:   10.682 ms/op
                 getUser·p0.999:  29.360 ms/op
                 getUser·p0.9999: 33.712 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 165764
  mean =      5.788 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 38369 
    [ 5.000,  7.500) = 114724 
    [ 7.500, 10.000) = 9200 
    [10.000, 12.500) = 2232 
    [12.500, 15.000) = 698 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.290 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     23.076 ms/op
     p(99.9900) =     34.936 ms/op
     p(99.9990) =     37.247 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 21.522 ±(99.9%) 0.412 ms/op
# Warmup Iteration   2: 8.419 ±(99.9%) 0.063 ms/op
# Warmup Iteration   3: 7.079 ±(99.9%) 0.031 ms/op
Iteration   1: 7.002 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.740 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   9.028 ms/op
                 listUser·p0.95:   10.726 ms/op
                 listUser·p0.99:   14.418 ms/op
                 listUser·p0.999:  27.744 ms/op
                 listUser·p0.9999: 30.817 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   2: 6.818 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   6.283 ms/op
                 listUser·p0.90:   8.487 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   14.483 ms/op
                 listUser·p0.999:  31.228 ms/op
                 listUser·p0.9999: 47.855 ms/op
                 listUser·p1.00:   48.759 ms/op

Iteration   3: 6.901 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   6.513 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   10.060 ms/op
                 listUser·p0.99:   13.648 ms/op
                 listUser·p0.999:  26.517 ms/op
                 listUser·p0.9999: 31.425 ms/op
                 listUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139049
  mean =      6.906 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2429 
    [ 5.000, 10.000) = 128881 
    [10.000, 15.000) = 6663 
    [15.000, 20.000) = 789 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 162 
    [30.000, 35.000) = 49 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      6.423 ms/op
     p(90.0000) =      8.618 ms/op
     p(95.0000) =     10.289 ms/op
     p(99.0000) =     14.205 ms/op
     p(99.9000) =     28.113 ms/op
     p(99.9900) =     46.989 ms/op
     p(99.9990) =     48.503 ms/op
     p(99.9999) =     48.759 ms/op
    p(100.0000) =     48.759 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.375 ± 3.897  ops/ms
ClientPb.existUser                       thrpt       3   5.856 ± 1.753  ops/ms
ClientPb.getUser                         thrpt       3   5.512 ± 1.272  ops/ms
ClientPb.listUser                        thrpt       3   4.431 ± 1.262  ops/ms
ClientPb.createUser                       avgt       3   5.889 ± 1.614   ms/op
ClientPb.existUser                        avgt       3   5.438 ± 1.037   ms/op
ClientPb.getUser                          avgt       3   5.852 ± 2.198   ms/op
ClientPb.listUser                         avgt       3   6.802 ± 1.346   ms/op
ClientPb.createUser                     sample  164421   5.834 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.192           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.649           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.460           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.999           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.322           ms/op
ClientPb.existUser                      sample  172252   5.565 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.401           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.036           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.158           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.886           ms/op
ClientPb.existUser:existUser·p0.9999    sample          41.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.383           ms/op
ClientPb.getUser                        sample  165764   5.788 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.600           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.076           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  139049   6.906 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.423           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.289           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.205           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.113           ms/op
ClientPb.listUser:listUser·p0.9999      sample          46.989           ms/op
ClientPb.listUser:listUser·p1.00        sample          48.759           ms/op
