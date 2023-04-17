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
# Warmup Iteration   1: 2.184 ops/ms
# Warmup Iteration   2: 5.959 ops/ms
# Warmup Iteration   3: 8.418 ops/ms
Iteration   1: 9.391 ops/ms
Iteration   2: 9.434 ops/ms
Iteration   3: 9.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.430 ±(99.9%) 0.668 ops/ms [Average]
  (min, avg, max) = (9.391, 9.430, 9.464), stdev = 0.037
  CI (99.9%): [8.762, 10.098] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ops/ms
# Warmup Iteration   2: 7.985 ops/ms
# Warmup Iteration   3: 9.711 ops/ms
Iteration   1: 9.509 ops/ms
Iteration   2: 9.599 ops/ms
Iteration   3: 9.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.573 ±(99.9%) 1.029 ops/ms [Average]
  (min, avg, max) = (9.509, 9.573, 9.613), stdev = 0.056
  CI (99.9%): [8.544, 10.602] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.096 ops/ms
# Warmup Iteration   2: 8.616 ops/ms
# Warmup Iteration   3: 8.985 ops/ms
Iteration   1: 8.966 ops/ms
Iteration   2: 9.674 ops/ms
Iteration   3: 9.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.424 ±(99.9%) 7.237 ops/ms [Average]
  (min, avg, max) = (8.966, 9.424, 9.674), stdev = 0.397
  CI (99.9%): [2.187, 16.660] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 7.649 ops/ms
Iteration   1: 7.725 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.008 ±(99.9%) 4.483 ops/ms [Average]
  (min, avg, max) = (7.725, 8.008, 8.154), stdev = 0.246
  CI (99.9%): [3.525, 12.492] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.403 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.004 ms/op
Iteration   1: 3.495 ±(99.9%) 0.004 ms/op
Iteration   2: 3.302 ±(99.9%) 0.010 ms/op
Iteration   3: 3.414 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.404 ±(99.9%) 1.770 ms/op [Average]
  (min, avg, max) = (3.302, 3.404, 3.495), stdev = 0.097
  CI (99.9%): [1.634, 5.173] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.598 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.008 ms/op
Iteration   1: 3.308 ±(99.9%) 0.012 ms/op
Iteration   2: 3.276 ±(99.9%) 0.007 ms/op
Iteration   3: 3.237 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.274 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.237, 3.274, 3.308), stdev = 0.035
  CI (99.9%): [2.628, 3.919] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.724 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.568 ±(99.9%) 0.007 ms/op
Iteration   1: 3.476 ±(99.9%) 0.005 ms/op
Iteration   2: 3.405 ±(99.9%) 0.005 ms/op
Iteration   3: 3.450 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.443 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.405, 3.443, 3.476), stdev = 0.036
  CI (99.9%): [2.786, 4.101] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.695 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.283 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
Iteration   2: 3.955 ±(99.9%) 0.008 ms/op
Iteration   3: 3.945 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.926 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.879, 3.926, 3.955), stdev = 0.041
  CI (99.9%): [3.176, 4.676] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.113 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.010 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  20.654 ms/op
                 createUser·p0.9999: 23.805 ms/op
                 createUser·p1.00:   26.837 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  21.605 ms/op
                 createUser·p0.9999: 24.711 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   3: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  19.477 ms/op
                 createUser·p0.9999: 24.892 ms/op
                 createUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279205
  mean =      3.436 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8595 
    [ 2.500,  5.000) = 262971 
    [ 5.000,  7.500) = 6307 
    [ 7.500, 10.000) = 727 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 146 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.971 ms/op
     p(99.9000) =     20.008 ms/op
     p(99.9900) =     24.548 ms/op
     p(99.9990) =     25.320 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.591 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.007 ms/op
Iteration   1: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  9.947 ms/op
                 existUser·p0.9999: 24.574 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 3.284 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.389 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  15.053 ms/op
                 existUser·p0.9999: 27.763 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.990 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  13.344 ms/op
                 existUser·p0.9999: 25.192 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292638
  mean =      3.277 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13564 
    [ 2.500,  5.000) = 272939 
    [ 5.000,  7.500) = 5233 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.772 ms/op
     p(99.9000) =     14.987 ms/op
     p(99.9900) =     26.730 ms/op
     p(99.9990) =     28.029 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 8.932 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.527 ±(99.9%) 0.011 ms/op
Iteration   1: 3.502 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  21.239 ms/op
                 getUser·p0.9999: 38.658 ms/op
                 getUser·p1.00:   40.370 ms/op

Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.343 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  11.843 ms/op
                 getUser·p0.9999: 27.296 ms/op
                 getUser·p1.00:   29.688 ms/op

Iteration   3: 3.502 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.130 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   4.014 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  9.254 ms/op
                 getUser·p0.9999: 24.754 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280280
  mean =      3.423 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 270734 
    [ 5.000, 10.000) = 9093 
    [10.000, 15.000) = 189 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 183 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     37.749 ms/op
     p(99.9990) =     39.779 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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
# Warmup Iteration   1: 10.425 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.199 ±(99.9%) 0.015 ms/op
Iteration   1: 4.233 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  21.483 ms/op
                 listUser·p0.9999: 25.425 ms/op
                 listUser·p1.00:   26.608 ms/op

Iteration   2: 3.969 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  17.021 ms/op
                 listUser·p0.9999: 23.036 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.851 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 17.531 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239131
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 227613 
    [ 5.000,  7.500) = 9147 
    [ 7.500, 10.000) = 1563 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     23.998 ms/op
     p(99.9990) =     26.078 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.430 ± 0.668  ops/ms
ClientPb.existUser                       thrpt       3   9.573 ± 1.029  ops/ms
ClientPb.getUser                         thrpt       3   9.424 ± 7.237  ops/ms
ClientPb.listUser                        thrpt       3   8.008 ± 4.483  ops/ms
ClientPb.createUser                       avgt       3   3.404 ± 1.770   ms/op
ClientPb.existUser                        avgt       3   3.274 ± 0.646   ms/op
ClientPb.getUser                          avgt       3   3.443 ± 0.657   ms/op
ClientPb.listUser                         avgt       3   3.926 ± 0.750   ms/op
ClientPb.createUser                     sample  279205   3.436 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.338           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.971           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.548           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.837           ms/op
ClientPb.existUser                      sample  292638   3.277 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.501           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.600           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.055           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.772           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.987           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  280280   3.423 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.130           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.767           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.565           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.749           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.370           ms/op
ClientPb.listUser                       sample  239131   4.011 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.255           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.531           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.998           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.608           ms/op
