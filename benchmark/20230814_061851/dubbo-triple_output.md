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
# Warmup Iteration   1: 2.015 ops/ms
# Warmup Iteration   2: 5.232 ops/ms
# Warmup Iteration   3: 8.547 ops/ms
Iteration   1: 8.841 ops/ms
Iteration   2: 8.804 ops/ms
Iteration   3: 8.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.815 ±(99.9%) 0.408 ops/ms [Average]
  (min, avg, max) = (8.800, 8.815, 8.841), stdev = 0.022
  CI (99.9%): [8.407, 9.223] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.581 ops/ms
# Warmup Iteration   2: 8.048 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 9.546 ops/ms
Iteration   3: 9.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.503 ±(99.9%) 2.279 ops/ms [Average]
  (min, avg, max) = (9.362, 9.503, 9.601), stdev = 0.125
  CI (99.9%): [7.224, 11.782] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.088 ops/ms
# Warmup Iteration   2: 8.282 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.748 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.089 ±(99.9%) 5.436 ops/ms [Average]
  (min, avg, max) = (8.748, 9.089, 9.299), stdev = 0.298
  CI (99.9%): [3.653, 14.524] (assumes normal distribution)


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
# Warmup Iteration   1: 2.723 ops/ms
# Warmup Iteration   2: 6.929 ops/ms
# Warmup Iteration   3: 7.318 ops/ms
Iteration   1: 7.454 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.688 ±(99.9%) 3.709 ops/ms [Average]
  (min, avg, max) = (7.454, 7.688, 7.821), stdev = 0.203
  CI (99.9%): [3.978, 11.397] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.918 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.040 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.005 ms/op
Iteration   1: 3.557 ±(99.9%) 0.007 ms/op
Iteration   2: 3.502 ±(99.9%) 0.006 ms/op
Iteration   3: 3.440 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.500 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.440, 3.500, 3.557), stdev = 0.059
  CI (99.9%): [2.431, 4.568] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.813 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.004 ms/op
Iteration   1: 3.414 ±(99.9%) 0.003 ms/op
Iteration   2: 3.505 ±(99.9%) 0.004 ms/op
Iteration   3: 3.421 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.447 ±(99.9%) 0.927 ms/op [Average]
  (min, avg, max) = (3.414, 3.447, 3.505), stdev = 0.051
  CI (99.9%): [2.519, 4.374] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.774 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.004 ms/op
Iteration   1: 3.480 ±(99.9%) 0.003 ms/op
Iteration   2: 3.461 ±(99.9%) 0.004 ms/op
Iteration   3: 3.521 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.487 ±(99.9%) 0.568 ms/op [Average]
  (min, avg, max) = (3.461, 3.487, 3.521), stdev = 0.031
  CI (99.9%): [2.919, 4.055] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.531 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.329 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.009 ms/op
Iteration   1: 4.156 ±(99.9%) 0.008 ms/op
Iteration   2: 4.111 ±(99.9%) 0.010 ms/op
Iteration   3: 4.127 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.131 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (4.111, 4.131, 4.156), stdev = 0.023
  CI (99.9%): [3.718, 4.544] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.670 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.627 ±(99.9%) 0.012 ms/op
Iteration   1: 3.577 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  22.891 ms/op
                 createUser·p0.9999: 31.293 ms/op
                 createUser·p1.00:   31.752 ms/op

Iteration   2: 3.542 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  24.107 ms/op
                 createUser·p0.9999: 28.275 ms/op
                 createUser·p1.00:   29.950 ms/op

Iteration   3: 3.622 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 30.152 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 268008
  mean =      3.580 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4763 
    [ 2.500,  5.000) = 254398 
    [ 5.000,  7.500) = 7222 
    [ 7.500, 10.000) = 1078 
    [10.000, 12.500) = 203 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.599 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     22.086 ms/op
     p(99.9900) =     30.612 ms/op
     p(99.9990) =     31.523 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.201 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.011 ms/op
Iteration   1: 3.500 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.780 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.047 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  17.744 ms/op
                 existUser·p0.9999: 20.082 ms/op
                 existUser·p1.00:   20.775 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  14.627 ms/op
                 existUser·p0.9999: 24.116 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   3: 3.557 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.589 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   4.133 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  20.543 ms/op
                 existUser·p0.9999: 32.376 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276577
  mean =      3.469 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4138 
    [ 2.500,  5.000) = 264329 
    [ 5.000,  7.500) = 6356 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 448 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     30.912 ms/op
     p(99.9990) =     32.729 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 10.559 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.015 ms/op
Iteration   1: 3.414 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  22.357 ms/op
                 getUser·p0.9999: 27.992 ms/op
                 getUser·p1.00:   28.115 ms/op

Iteration   2: 3.496 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  22.790 ms/op
                 getUser·p0.9999: 34.275 ms/op
                 getUser·p1.00:   35.652 ms/op

Iteration   3: 3.457 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  11.085 ms/op
                 getUser·p0.9999: 27.222 ms/op
                 getUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277647
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4204 
    [ 2.500,  5.000) = 266785 
    [ 5.000,  7.500) = 5022 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     17.970 ms/op
     p(99.9900) =     32.620 ms/op
     p(99.9990) =     35.026 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 11.365 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.015 ms/op
Iteration   1: 4.216 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  22.749 ms/op
                 listUser·p0.9999: 28.030 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.162 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.873 ms/op
                 listUser·p0.999:  17.133 ms/op
                 listUser·p0.9999: 24.740 ms/op
                 listUser·p1.00:   24.805 ms/op

Iteration   3: 4.099 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.923 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  15.869 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230944
  mean =      4.158 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 218546 
    [ 5.000,  7.500) = 8776 
    [ 7.500, 10.000) = 2194 
    [10.000, 12.500) = 804 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     26.539 ms/op
     p(99.9990) =     28.248 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.815 ± 0.408  ops/ms
ClientPb.existUser                       thrpt       3   9.503 ± 2.279  ops/ms
ClientPb.getUser                         thrpt       3   9.089 ± 5.436  ops/ms
ClientPb.listUser                        thrpt       3   7.688 ± 3.709  ops/ms
ClientPb.createUser                       avgt       3   3.500 ± 1.068   ms/op
ClientPb.existUser                        avgt       3   3.447 ± 0.927   ms/op
ClientPb.getUser                          avgt       3   3.487 ± 0.568   ms/op
ClientPb.listUser                         avgt       3   4.131 ± 0.413   ms/op
ClientPb.createUser                     sample  268008   3.580 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.599           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.108           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.668           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.612           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  276577   3.469 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.251           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.530           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.695           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.912           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.456           ms/op
ClientPb.getUser                        sample  277647   3.456 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.047           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.300           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.970           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.620           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  230944   4.158 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.079           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.465           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.539           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
