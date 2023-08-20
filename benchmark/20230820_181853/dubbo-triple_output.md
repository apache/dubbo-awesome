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
# Warmup Iteration   1: 1.105 ops/ms
# Warmup Iteration   2: 2.312 ops/ms
# Warmup Iteration   3: 5.233 ops/ms
Iteration   1: 5.606 ops/ms
Iteration   2: 5.679 ops/ms
Iteration   3: 5.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.699 ±(99.9%) 1.899 ops/ms [Average]
  (min, avg, max) = (5.606, 5.699, 5.811), stdev = 0.104
  CI (99.9%): [3.800, 7.598] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.524 ops/ms
# Warmup Iteration   2: 4.428 ops/ms
# Warmup Iteration   3: 5.685 ops/ms
Iteration   1: 6.221 ops/ms
Iteration   2: 6.160 ops/ms
Iteration   3: 5.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.117 ±(99.9%) 2.387 ops/ms [Average]
  (min, avg, max) = (5.970, 6.117, 6.221), stdev = 0.131
  CI (99.9%): [3.730, 8.504] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.699 ops/ms
# Warmup Iteration   2: 4.732 ops/ms
# Warmup Iteration   3: 5.633 ops/ms
Iteration   1: 5.660 ops/ms
Iteration   2: 5.736 ops/ms
Iteration   3: 5.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.734 ±(99.9%) 1.331 ops/ms [Average]
  (min, avg, max) = (5.660, 5.734, 5.806), stdev = 0.073
  CI (99.9%): [4.403, 7.065] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.544 ops/ms
# Warmup Iteration   2: 3.723 ops/ms
# Warmup Iteration   3: 5.054 ops/ms
Iteration   1: 4.776 ops/ms
Iteration   2: 4.659 ops/ms
Iteration   3: 5.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.830 ±(99.9%) 3.717 ops/ms [Average]
  (min, avg, max) = (4.659, 4.830, 5.056), stdev = 0.204
  CI (99.9%): [1.113, 8.548] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 18.939 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.502 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.993 ±(99.9%) 0.007 ms/op
Iteration   1: 5.495 ±(99.9%) 0.018 ms/op
Iteration   2: 5.772 ±(99.9%) 0.009 ms/op
Iteration   3: 5.681 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.649 ±(99.9%) 2.577 ms/op [Average]
  (min, avg, max) = (5.495, 5.649, 5.772), stdev = 0.141
  CI (99.9%): [3.072, 8.226] (assumes normal distribution)


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
# Warmup Iteration   1: 17.853 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 6.409 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.347 ±(99.9%) 0.010 ms/op
Iteration   1: 5.422 ±(99.9%) 0.007 ms/op
Iteration   2: 5.377 ±(99.9%) 0.012 ms/op
Iteration   3: 5.257 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.352 ±(99.9%) 1.555 ms/op [Average]
  (min, avg, max) = (5.257, 5.352, 5.422), stdev = 0.085
  CI (99.9%): [3.798, 6.907] (assumes normal distribution)


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
# Warmup Iteration   1: 17.625 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.510 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.635 ±(99.9%) 0.013 ms/op
Iteration   1: 5.697 ±(99.9%) 0.010 ms/op
Iteration   2: 5.704 ±(99.9%) 0.008 ms/op
Iteration   3: 5.531 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.644 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (5.531, 5.644, 5.704), stdev = 0.098
  CI (99.9%): [3.862, 7.427] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.293 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 7.341 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.664 ±(99.9%) 0.009 ms/op
Iteration   1: 6.369 ±(99.9%) 0.014 ms/op
Iteration   2: 6.661 ±(99.9%) 0.018 ms/op
Iteration   3: 6.300 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.444 ±(99.9%) 3.499 ms/op [Average]
  (min, avg, max) = (6.300, 6.444, 6.661), stdev = 0.192
  CI (99.9%): [2.945, 9.943] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 19.211 ±(99.9%) 0.327 ms/op
# Warmup Iteration   2: 7.438 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.229 ±(99.9%) 0.030 ms/op
Iteration   1: 5.709 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.390 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   7.807 ms/op
                 createUser·p0.99:   10.699 ms/op
                 createUser·p0.999:  15.809 ms/op
                 createUser·p0.9999: 30.720 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   2: 5.466 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.634 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.094 ms/op
                 createUser·p0.99:   10.465 ms/op
                 createUser·p0.999:  26.623 ms/op
                 createUser·p0.9999: 33.620 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   3: 5.676 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.111 ms/op
                 createUser·p0.95:   7.971 ms/op
                 createUser·p0.99:   10.093 ms/op
                 createUser·p0.999:  28.266 ms/op
                 createUser·p0.9999: 31.772 ms/op
                 createUser·p1.00:   32.375 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 170939
  mean =      5.615 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 46160 
    [ 5.000,  7.500) = 114943 
    [ 7.500, 10.000) = 7822 
    [10.000, 12.500) = 1461 
    [12.500, 15.000) = 310 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.585 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.355 ms/op
     p(99.9000) =     17.834 ms/op
     p(99.9900) =     32.762 ms/op
     p(99.9990) =     35.288 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 16.875 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 6.617 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.656 ±(99.9%) 0.023 ms/op
Iteration   1: 5.300 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.638 ms/op
                 existUser·p0.50:   4.940 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.299 ms/op
                 existUser·p0.99:   9.683 ms/op
                 existUser·p0.999:  26.051 ms/op
                 existUser·p0.9999: 28.671 ms/op
                 existUser·p1.00:   29.786 ms/op

Iteration   2: 5.218 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   4.932 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.021 ms/op
                 existUser·p0.99:   10.144 ms/op
                 existUser·p0.999:  16.073 ms/op
                 existUser·p0.9999: 28.983 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   3: 5.402 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.017 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.611 ms/op
                 existUser·p0.95:   7.471 ms/op
                 existUser·p0.99:   10.060 ms/op
                 existUser·p0.999:  29.118 ms/op
                 existUser·p0.9999: 33.146 ms/op
                 existUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180738
  mean =      5.305 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 92260 
    [ 5.000,  7.500) = 80749 
    [ 7.500, 10.000) = 5975 
    [10.000, 12.500) = 1099 
    [12.500, 15.000) = 327 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      4.981 ms/op
     p(90.0000) =      6.488 ms/op
     p(95.0000) =      7.283 ms/op
     p(99.0000) =      9.929 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     31.160 ms/op
     p(99.9990) =     34.034 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 18.359 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 7.077 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.714 ±(99.9%) 0.023 ms/op
Iteration   1: 5.760 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   5.407 ms/op
                 getUser·p0.90:   7.012 ms/op
                 getUser·p0.95:   8.061 ms/op
                 getUser·p0.99:   11.829 ms/op
                 getUser·p0.999:  26.475 ms/op
                 getUser·p0.9999: 29.390 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   2: 5.631 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.095 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.864 ms/op
                 getUser·p0.99:   11.829 ms/op
                 getUser·p0.999:  21.561 ms/op
                 getUser·p0.9999: 33.989 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   3: 5.729 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.896 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   6.726 ms/op
                 getUser·p0.95:   7.840 ms/op
                 getUser·p0.99:   11.698 ms/op
                 getUser·p0.999:  28.747 ms/op
                 getUser·p0.9999: 31.675 ms/op
                 getUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 168181
  mean =      5.706 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 41825 
    [ 5.000,  7.500) = 115915 
    [ 7.500, 10.000) = 7123 
    [10.000, 12.500) = 2077 
    [12.500, 15.000) = 749 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.737 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.840 ms/op
     p(95.0000) =      7.930 ms/op
     p(99.0000) =     11.780 ms/op
     p(99.9000) =     23.274 ms/op
     p(99.9900) =     33.307 ms/op
     p(99.9990) =     34.943 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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
# Warmup Iteration   1: 22.335 ±(99.9%) 0.354 ms/op
# Warmup Iteration   2: 8.495 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.906 ±(99.9%) 0.031 ms/op
Iteration   1: 6.534 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   3.125 ms/op
                 listUser·p0.50:   6.119 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   12.954 ms/op
                 listUser·p0.999:  29.131 ms/op
                 listUser·p0.9999: 32.461 ms/op
                 listUser·p1.00:   33.325 ms/op

Iteration   2: 6.944 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   6.578 ms/op
                 listUser·p0.90:   8.387 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   13.124 ms/op
                 listUser·p0.999:  28.888 ms/op
                 listUser·p0.9999: 33.514 ms/op
                 listUser·p1.00:   34.603 ms/op

Iteration   3: 6.610 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   13.375 ms/op
                 listUser·p0.999:  40.412 ms/op
                 listUser·p0.9999: 47.579 ms/op
                 listUser·p1.00:   47.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 143431
  mean =      6.692 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3195 
    [ 5.000, 10.000) = 134408 
    [10.000, 15.000) = 5186 
    [15.000, 20.000) = 330 
    [20.000, 25.000) = 73 
    [25.000, 30.000) = 102 
    [30.000, 35.000) = 73 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      6.275 ms/op
     p(90.0000) =      7.979 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     13.091 ms/op
     p(99.9000) =     29.622 ms/op
     p(99.9900) =     44.497 ms/op
     p(99.9990) =     47.944 ms/op
     p(99.9999) =     47.972 ms/op
    p(100.0000) =     47.972 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.699 ± 1.899  ops/ms
ClientPb.existUser                       thrpt       3   6.117 ± 2.387  ops/ms
ClientPb.getUser                         thrpt       3   5.734 ± 1.331  ops/ms
ClientPb.listUser                        thrpt       3   4.830 ± 3.717  ops/ms
ClientPb.createUser                       avgt       3   5.649 ± 2.577   ms/op
ClientPb.existUser                        avgt       3   5.352 ± 1.555   ms/op
ClientPb.getUser                          avgt       3   5.644 ± 1.782   ms/op
ClientPb.listUser                         avgt       3   6.444 ± 3.499   ms/op
ClientPb.createUser                     sample  170939   5.615 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.585           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.300           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.857           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.676           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.355           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.834           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.762           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521           ms/op
ClientPb.existUser                      sample  180738   5.305 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.854           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.488           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.283           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.929           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.302           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.160           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.669           ms/op
ClientPb.getUser                        sample  168181   5.706 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.737           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.374           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.840           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.930           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.780           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.274           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.307           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  143431   6.692 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.275           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.979           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.091           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.622           ms/op
ClientPb.listUser:listUser·p0.9999      sample          44.497           ms/op
ClientPb.listUser:listUser·p1.00        sample          47.972           ms/op
