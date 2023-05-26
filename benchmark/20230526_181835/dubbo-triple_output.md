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
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 5.133 ops/ms
# Warmup Iteration   3: 8.528 ops/ms
Iteration   1: 9.242 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.287 ±(99.9%) 0.929 ops/ms [Average]
  (min, avg, max) = (9.242, 9.287, 9.342), stdev = 0.051
  CI (99.9%): [8.358, 10.216] (assumes normal distribution)


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
# Warmup Iteration   1: 3.091 ops/ms
# Warmup Iteration   2: 8.827 ops/ms
# Warmup Iteration   3: 9.274 ops/ms
Iteration   1: 9.723 ops/ms
Iteration   2: 9.872 ops/ms
Iteration   3: 9.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.864 ±(99.9%) 2.508 ops/ms [Average]
  (min, avg, max) = (9.723, 9.864, 9.997), stdev = 0.137
  CI (99.9%): [7.356, 12.372] (assumes normal distribution)


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
# Warmup Iteration   1: 2.582 ops/ms
# Warmup Iteration   2: 8.103 ops/ms
# Warmup Iteration   3: 9.504 ops/ms
Iteration   1: 9.469 ops/ms
Iteration   2: 9.162 ops/ms
Iteration   3: 9.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.392 ±(99.9%) 3.702 ops/ms [Average]
  (min, avg, max) = (9.162, 9.392, 9.546), stdev = 0.203
  CI (99.9%): [5.690, 13.095] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.658 ops/ms
# Warmup Iteration   2: 7.143 ops/ms
# Warmup Iteration   3: 7.869 ops/ms
Iteration   1: 7.835 ops/ms
Iteration   2: 8.387 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.087 ±(99.9%) 5.098 ops/ms [Average]
  (min, avg, max) = (7.835, 8.087, 8.387), stdev = 0.279
  CI (99.9%): [2.989, 13.186] (assumes normal distribution)


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
# Warmup Iteration   1: 10.827 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.938 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.009 ms/op
Iteration   1: 3.453 ±(99.9%) 0.005 ms/op
Iteration   2: 3.474 ±(99.9%) 0.004 ms/op
Iteration   3: 3.362 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.429 ±(99.9%) 1.089 ms/op [Average]
  (min, avg, max) = (3.362, 3.429, 3.474), stdev = 0.060
  CI (99.9%): [2.341, 4.518] (assumes normal distribution)


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
# Warmup Iteration   1: 9.648 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.003 ms/op
Iteration   1: 3.208 ±(99.9%) 0.008 ms/op
Iteration   2: 3.230 ±(99.9%) 0.013 ms/op
Iteration   3: 3.339 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.259 ±(99.9%) 1.280 ms/op [Average]
  (min, avg, max) = (3.208, 3.259, 3.339), stdev = 0.070
  CI (99.9%): [1.979, 4.539] (assumes normal distribution)


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
# Warmup Iteration   1: 10.721 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.006 ms/op
Iteration   1: 3.512 ±(99.9%) 0.009 ms/op
Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.434 ±(99.9%) 1.352 ms/op [Average]
  (min, avg, max) = (3.364, 3.434, 3.512), stdev = 0.074
  CI (99.9%): [2.082, 4.786] (assumes normal distribution)


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
# Warmup Iteration   1: 11.297 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.312 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.143 ±(99.9%) 0.007 ms/op
Iteration   1: 4.037 ±(99.9%) 0.008 ms/op
Iteration   2: 4.079 ±(99.9%) 0.005 ms/op
Iteration   3: 3.913 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.010 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.913, 4.010, 4.079), stdev = 0.086
  CI (99.9%): [2.437, 5.582] (assumes normal distribution)


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
# Warmup Iteration   1: 10.866 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.291 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.013 ms/op
Iteration   1: 3.355 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  23.640 ms/op
                 createUser·p0.9999: 29.032 ms/op
                 createUser·p1.00:   30.376 ms/op

Iteration   2: 3.349 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  23.342 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.366 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  20.411 ms/op
                 createUser·p0.9999: 32.063 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 285627
  mean =      3.357 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16744 
    [ 2.500,  5.000) = 262887 
    [ 5.000,  7.500) = 4855 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.492 ms/op
     p(99.9900) =     29.585 ms/op
     p(99.9990) =     32.623 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.678 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.009 ms/op
Iteration   1: 3.463 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.559 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   4.055 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  23.907 ms/op
                 existUser·p0.9999: 26.354 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   2: 3.330 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.221 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  23.690 ms/op
                 existUser·p0.9999: 29.137 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.653 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.587 ms/op
                 existUser·p0.999:  10.484 ms/op
                 existUser·p0.9999: 30.120 ms/op
                 existUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284516
  mean =      3.373 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9086 
    [ 2.500,  5.000) = 268542 
    [ 5.000,  7.500) = 5816 
    [ 7.500, 10.000) = 592 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 129 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     12.894 ms/op
     p(99.9900) =     29.003 ms/op
     p(99.9990) =     31.853 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 10.225 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
Iteration   1: 3.480 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.903 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   7.307 ms/op
                 getUser·p0.999:  21.529 ms/op
                 getUser·p0.9999: 31.845 ms/op
                 getUser·p1.00:   33.227 ms/op

Iteration   2: 3.365 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.177 ms/op
                 getUser·p0.999:  23.564 ms/op
                 getUser·p0.9999: 27.066 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   3: 3.537 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.357 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   5.087 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  20.224 ms/op
                 getUser·p0.9999: 29.685 ms/op
                 getUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277435
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7969 
    [ 2.500,  5.000) = 258942 
    [ 5.000,  7.500) = 8958 
    [ 7.500, 10.000) = 1018 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     30.810 ms/op
     p(99.9990) =     32.529 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 11.188 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.445 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.178 ±(99.9%) 0.015 ms/op
Iteration   1: 4.026 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  21.645 ms/op
                 listUser·p0.9999: 26.640 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 4.042 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 19.762 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.617 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 19.868 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237478
  mean =      4.040 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 226673 
    [ 5.000,  7.500) = 7895 
    [ 7.500, 10.000) = 1871 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     17.777 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     27.730 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.287 ± 0.929  ops/ms
ClientPb.existUser                       thrpt       3   9.864 ± 2.508  ops/ms
ClientPb.getUser                         thrpt       3   9.392 ± 3.702  ops/ms
ClientPb.listUser                        thrpt       3   8.087 ± 5.098  ops/ms
ClientPb.createUser                       avgt       3   3.429 ± 1.089   ms/op
ClientPb.existUser                        avgt       3   3.259 ± 1.280   ms/op
ClientPb.getUser                          avgt       3   3.434 ± 1.352   ms/op
ClientPb.listUser                         avgt       3   4.010 ± 1.572   ms/op
ClientPb.createUser                     sample  285627   3.357 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.180           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.005           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.492           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.585           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.735           ms/op
ClientPb.existUser                      sample  284516   3.373 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.221           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.284           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.894           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.003           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  277435   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.357           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.289           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.881           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.810           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.227           ms/op
ClientPb.listUser                       sample  237478   4.040 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.980           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.807           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.919           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.853           ms/op
