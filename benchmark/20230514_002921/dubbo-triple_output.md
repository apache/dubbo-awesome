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
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 4.370 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 9.455 ops/ms
Iteration   2: 9.299 ops/ms
Iteration   3: 9.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.354 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (9.299, 9.354, 9.455), stdev = 0.088
  CI (99.9%): [7.745, 10.962] (assumes normal distribution)


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
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 8.776 ops/ms
# Warmup Iteration   3: 9.691 ops/ms
Iteration   1: 9.882 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 9.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.793 ±(99.9%) 6.516 ops/ms [Average]
  (min, avg, max) = (9.399, 9.793, 10.096), stdev = 0.357
  CI (99.9%): [3.277, 16.309] (assumes normal distribution)


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
# Warmup Iteration   1: 2.710 ops/ms
# Warmup Iteration   2: 8.371 ops/ms
# Warmup Iteration   3: 9.273 ops/ms
Iteration   1: 9.111 ops/ms
Iteration   2: 9.292 ops/ms
Iteration   3: 9.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.153 ±(99.9%) 2.250 ops/ms [Average]
  (min, avg, max) = (9.057, 9.153, 9.292), stdev = 0.123
  CI (99.9%): [6.903, 11.404] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.433 ops/ms
# Warmup Iteration   2: 6.914 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.279 ops/ms
Iteration   2: 8.158 ops/ms
Iteration   3: 8.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.237 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (8.158, 8.237, 8.279), stdev = 0.069
  CI (99.9%): [6.981, 9.493] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.912 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.009 ms/op
Iteration   1: 3.315 ±(99.9%) 0.004 ms/op
Iteration   2: 3.359 ±(99.9%) 0.008 ms/op
Iteration   3: 3.547 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.407 ±(99.9%) 2.245 ms/op [Average]
  (min, avg, max) = (3.315, 3.407, 3.547), stdev = 0.123
  CI (99.9%): [1.162, 5.652] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.974 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.006 ms/op
Iteration   1: 3.271 ±(99.9%) 0.011 ms/op
Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
Iteration   3: 3.130 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.213 ±(99.9%) 1.350 ms/op [Average]
  (min, avg, max) = (3.130, 3.213, 3.271), stdev = 0.074
  CI (99.9%): [1.863, 4.563] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.881 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.003 ms/op
Iteration   1: 3.376 ±(99.9%) 0.006 ms/op
Iteration   2: 3.278 ±(99.9%) 0.012 ms/op
Iteration   3: 3.328 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.327 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (3.278, 3.327, 3.376), stdev = 0.049
  CI (99.9%): [2.434, 4.221] (assumes normal distribution)


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
# Warmup Iteration   1: 10.504 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.167 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.007 ms/op
Iteration   1: 3.859 ±(99.9%) 0.011 ms/op
Iteration   2: 3.782 ±(99.9%) 0.012 ms/op
Iteration   3: 3.878 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.840 ±(99.9%) 0.926 ms/op [Average]
  (min, avg, max) = (3.782, 3.840, 3.878), stdev = 0.051
  CI (99.9%): [2.914, 4.766] (assumes normal distribution)


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
# Warmup Iteration   1: 8.840 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.783 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.010 ms/op
Iteration   1: 3.329 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  19.758 ms/op
                 createUser·p0.9999: 28.672 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   2: 3.400 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   6.145 ms/op
                 createUser·p0.999:  22.024 ms/op
                 createUser·p0.9999: 26.859 ms/op
                 createUser·p1.00:   27.591 ms/op

Iteration   3: 3.363 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.346 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  20.934 ms/op
                 createUser·p0.9999: 35.585 ms/op
                 createUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284998
  mean =      3.364 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7778 
    [ 2.500,  5.000) = 271857 
    [ 5.000,  7.500) = 4249 
    [ 7.500, 10.000) = 582 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     19.857 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     35.907 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


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
# Warmup Iteration   1: 8.714 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  8.438 ms/op
                 existUser·p0.9999: 22.360 ms/op
                 existUser·p1.00:   23.003 ms/op

Iteration   2: 3.260 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.649 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.748 ms/op
                 existUser·p0.999:  15.980 ms/op
                 existUser·p0.9999: 24.818 ms/op
                 existUser·p1.00:   25.133 ms/op

Iteration   3: 3.272 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294004
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17789 
    [ 2.500,  5.000) = 270724 
    [ 5.000,  7.500) = 4416 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 141 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     11.731 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.071 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


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
# Warmup Iteration   1: 9.777 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.011 ms/op
Iteration   1: 3.457 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  11.271 ms/op
                 getUser·p0.9999: 21.922 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  20.640 ms/op
                 getUser·p0.9999: 25.748 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 3.433 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.464 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  20.310 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281714
  mean =      3.406 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6112 
    [ 2.500,  5.000) = 267622 
    [ 5.000,  7.500) = 6791 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.174 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     15.038 ms/op
     p(99.9900) =     25.449 ms/op
     p(99.9990) =     27.931 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 10.406 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
Iteration   1: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.606 ms/op
                 listUser·p0.999:  18.654 ms/op
                 listUser·p0.9999: 22.669 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.999 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 3.914 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.118 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  13.593 ms/op
                 listUser·p0.9999: 19.054 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243523
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 235164 
    [ 5.000,  7.500) = 5899 
    [ 7.500, 10.000) = 1458 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.486 ms/op
     p(99.9000) =     15.138 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     24.327 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.354 ± 1.608  ops/ms
ClientPb.existUser                       thrpt       3   9.793 ± 6.516  ops/ms
ClientPb.getUser                         thrpt       3   9.153 ± 2.250  ops/ms
ClientPb.listUser                        thrpt       3   8.237 ± 1.256  ops/ms
ClientPb.createUser                       avgt       3   3.407 ± 2.245   ms/op
ClientPb.existUser                        avgt       3   3.213 ± 1.350   ms/op
ClientPb.getUser                          avgt       3   3.327 ± 0.894   ms/op
ClientPb.listUser                         avgt       3   3.840 ± 0.926   ms/op
ClientPb.createUser                     sample  284998   3.364 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.346           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.084           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.857           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.295           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  294004   3.264 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.948           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.731           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.593           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.133           ms/op
ClientPb.getUser                        sample  281714   3.406 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.174           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.277           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.129           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.038           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.449           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  243523   3.940 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.486           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.446           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.642           ms/op
