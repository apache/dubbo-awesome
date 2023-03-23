# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.155 ops/ms
# Warmup Iteration   2: 5.242 ops/ms
# Warmup Iteration   3: 8.471 ops/ms
Iteration   1: 9.121 ops/ms
Iteration   2: 9.205 ops/ms
Iteration   3: 9.492 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.273 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (9.121, 9.273, 9.492), stdev = 0.195
  CI (99.9%): [5.718, 12.827] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.148 ops/ms
# Warmup Iteration   2: 8.402 ops/ms
# Warmup Iteration   3: 9.655 ops/ms
Iteration   1: 9.855 ops/ms
Iteration   2: 9.680 ops/ms
Iteration   3: 9.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.742 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (9.680, 9.742, 9.855), stdev = 0.098
  CI (99.9%): [7.956, 11.528] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 8.331 ops/ms
# Warmup Iteration   3: 8.855 ops/ms
Iteration   1: 8.913 ops/ms
Iteration   2: 8.861 ops/ms
Iteration   3: 9.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.975 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (8.861, 8.975, 9.152), stdev = 0.155
  CI (99.9%): [6.147, 11.804] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.554 ops/ms
# Warmup Iteration   2: 6.689 ops/ms
# Warmup Iteration   3: 8.004 ops/ms
Iteration   1: 8.050 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.091 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (7.949, 8.091, 8.273), stdev = 0.166
  CI (99.9%): [5.067, 11.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.663 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.007 ms/op
Iteration   1: 3.517 ±(99.9%) 0.006 ms/op
Iteration   2: 3.392 ±(99.9%) 0.011 ms/op
Iteration   3: 3.444 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.451 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (3.392, 3.451, 3.517), stdev = 0.063
  CI (99.9%): [2.306, 4.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.343 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.008 ms/op
Iteration   1: 3.336 ±(99.9%) 0.003 ms/op
Iteration   2: 3.358 ±(99.9%) 0.004 ms/op
Iteration   3: 3.244 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.313 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.244, 3.313, 3.358), stdev = 0.061
  CI (99.9%): [2.207, 4.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.439 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.501 ±(99.9%) 0.005 ms/op
Iteration   1: 3.449 ±(99.9%) 0.012 ms/op
Iteration   2: 3.443 ±(99.9%) 0.005 ms/op
Iteration   3: 3.326 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.406 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.326, 3.406, 3.449), stdev = 0.069
  CI (99.9%): [2.140, 4.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.745 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.948 ±(99.9%) 0.011 ms/op
Iteration   2: 3.899 ±(99.9%) 0.015 ms/op
Iteration   3: 3.819 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.889 ±(99.9%) 1.182 ms/op [Average]
  (min, avg, max) = (3.819, 3.889, 3.948), stdev = 0.065
  CI (99.9%): [2.706, 5.071] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.272 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.067 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.011 ms/op
Iteration   1: 3.442 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.039 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  21.103 ms/op
                 createUser·p0.9999: 23.911 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.428 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.153 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  23.287 ms/op
                 createUser·p0.9999: 26.520 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.401 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  19.135 ms/op
                 createUser·p0.9999: 27.820 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279197
  mean =      3.436 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10815 
    [ 2.500,  5.000) = 263219 
    [ 5.000,  7.500) = 4242 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 131 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     19.877 ms/op
     p(99.9900) =     27.074 ms/op
     p(99.9990) =     28.056 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.940 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
Iteration   1: 3.358 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.165 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 26.064 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   2: 3.315 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  18.781 ms/op
                 existUser·p0.9999: 30.295 ms/op
                 existUser·p1.00:   31.031 ms/op

Iteration   3: 3.302 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  17.882 ms/op
                 existUser·p0.9999: 30.561 ms/op
                 existUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288461
  mean =      3.325 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7790 
    [ 2.500,  5.000) = 274982 
    [ 5.000,  7.500) = 4761 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.165 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     29.857 ms/op
     p(99.9990) =     31.046 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.287 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.012 ms/op
Iteration   1: 3.529 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  21.389 ms/op
                 getUser·p0.9999: 28.148 ms/op
                 getUser·p1.00:   29.164 ms/op

Iteration   2: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.839 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  10.527 ms/op
                 getUser·p0.9999: 33.640 ms/op
                 getUser·p1.00:   34.406 ms/op

Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  19.779 ms/op
                 getUser·p0.9999: 28.563 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277484
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7188 
    [ 2.500,  5.000) = 262871 
    [ 5.000,  7.500) = 6184 
    [ 7.500, 10.000) = 760 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 40 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.470 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.013 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 4.108 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  16.043 ms/op
                 listUser·p0.9999: 20.264 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.097 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.580 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.332 ms/op
                 listUser·p0.999:  14.612 ms/op
                 listUser·p0.9999: 17.275 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234992
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 225657 
    [ 5.000,  7.500) = 6870 
    [ 7.500, 10.000) = 1693 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 201 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.602 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.246 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.273 ± 3.555  ops/ms
ClientPb.existUser                       thrpt       3   9.742 ± 1.786  ops/ms
ClientPb.getUser                         thrpt       3   8.975 ± 2.828  ops/ms
ClientPb.listUser                        thrpt       3   8.091 ± 3.023  ops/ms
ClientPb.createUser                       avgt       3   3.451 ± 1.145   ms/op
ClientPb.existUser                        avgt       3   3.313 ± 1.106   ms/op
ClientPb.getUser                          avgt       3   3.406 ± 1.265   ms/op
ClientPb.listUser                         avgt       3   3.889 ± 1.182   ms/op
ClientPb.createUser                     sample  279197   3.436 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.938           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.587           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.877           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.312           ms/op
ClientPb.existUser                      sample  288461   3.325 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.165           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.108           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.767           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.616           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.857           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.228           ms/op
ClientPb.getUser                        sample  277484   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.180           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.858           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.283           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.416           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.030           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.406           ms/op
ClientPb.listUser                       sample  234992   4.085 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
