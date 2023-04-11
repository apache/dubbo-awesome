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
# Warmup Iteration   1: 2.095 ops/ms
# Warmup Iteration   2: 5.661 ops/ms
# Warmup Iteration   3: 8.642 ops/ms
Iteration   1: 9.060 ops/ms
Iteration   2: 9.294 ops/ms
Iteration   3: 9.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.180 ±(99.9%) 2.139 ops/ms [Average]
  (min, avg, max) = (9.060, 9.180, 9.294), stdev = 0.117
  CI (99.9%): [7.041, 11.320] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.442 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.502 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 9.580 ops/ms
Iteration   3: 9.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.459 ±(99.9%) 2.901 ops/ms [Average]
  (min, avg, max) = (9.279, 9.459, 9.580), stdev = 0.159
  CI (99.9%): [6.558, 12.360] (assumes normal distribution)


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
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 8.553 ops/ms
# Warmup Iteration   3: 9.271 ops/ms
Iteration   1: 9.358 ops/ms
Iteration   2: 9.574 ops/ms
Iteration   3: 9.318 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.416 ±(99.9%) 2.513 ops/ms [Average]
  (min, avg, max) = (9.318, 9.416, 9.574), stdev = 0.138
  CI (99.9%): [6.904, 11.929] (assumes normal distribution)


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
# Warmup Iteration   1: 2.934 ops/ms
# Warmup Iteration   2: 7.300 ops/ms
# Warmup Iteration   3: 7.914 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 7.802 ops/ms
Iteration   3: 8.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.017 ±(99.9%) 3.473 ops/ms [Average]
  (min, avg, max) = (7.802, 8.017, 8.166), stdev = 0.190
  CI (99.9%): [4.544, 11.490] (assumes normal distribution)


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
# Warmup Iteration   1: 9.742 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.008 ms/op
Iteration   1: 3.592 ±(99.9%) 0.005 ms/op
Iteration   2: 3.447 ±(99.9%) 0.006 ms/op
Iteration   3: 3.457 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.499 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.447, 3.499, 3.592), stdev = 0.081
  CI (99.9%): [2.017, 4.980] (assumes normal distribution)


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
# Warmup Iteration   1: 8.803 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.003 ms/op
Iteration   1: 3.328 ±(99.9%) 0.009 ms/op
Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
Iteration   3: 3.321 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (3.226, 3.292, 3.328), stdev = 0.057
  CI (99.9%): [2.249, 4.334] (assumes normal distribution)


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
# Warmup Iteration   1: 8.778 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.004 ms/op
Iteration   1: 3.392 ±(99.9%) 0.003 ms/op
Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
Iteration   3: 3.371 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.371 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.351, 3.371, 3.392), stdev = 0.021
  CI (99.9%): [2.996, 3.746] (assumes normal distribution)


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
# Warmup Iteration   1: 9.406 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.011 ms/op
Iteration   1: 3.959 ±(99.9%) 0.010 ms/op
Iteration   2: 3.863 ±(99.9%) 0.014 ms/op
Iteration   3: 3.969 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.930 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.863, 3.930, 3.969), stdev = 0.059
  CI (99.9%): [2.858, 5.003] (assumes normal distribution)


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
# Warmup Iteration   1: 8.728 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.009 ms/op
Iteration   1: 3.517 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.301 ms/op
                 createUser·p0.99:   6.373 ms/op
                 createUser·p0.999:  18.645 ms/op
                 createUser·p0.9999: 20.999 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.626 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  19.516 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   3: 3.482 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  21.398 ms/op
                 createUser·p0.9999: 31.961 ms/op
                 createUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276648
  mean =      3.467 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4076 
    [ 2.500,  5.000) = 267483 
    [ 5.000,  7.500) = 4057 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     18.776 ms/op
     p(99.9900) =     29.732 ms/op
     p(99.9990) =     32.342 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 7.501 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
Iteration   1: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.942 ms/op
                 existUser·p0.999:  19.567 ms/op
                 existUser·p0.9999: 22.397 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.451 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  20.796 ms/op
                 existUser·p0.9999: 30.564 ms/op
                 existUser·p1.00:   31.850 ms/op

Iteration   3: 3.276 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.288 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.133 ms/op
                 existUser·p0.9999: 25.862 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285183
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15044 
    [ 2.500,  5.000) = 264082 
    [ 5.000,  7.500) = 5245 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     18.508 ms/op
     p(99.9900) =     29.261 ms/op
     p(99.9990) =     31.719 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 9.781 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.522 ±(99.9%) 0.010 ms/op
Iteration   1: 3.570 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  18.065 ms/op
                 getUser·p0.9999: 24.970 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   2: 3.401 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  22.279 ms/op
                 getUser·p0.9999: 25.972 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   3: 3.382 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.775 ms/op
                 getUser·p0.999:  20.687 ms/op
                 getUser·p0.9999: 31.883 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278180
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2778 
    [ 2.500,  5.000) = 269037 
    [ 5.000,  7.500) = 5030 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.460 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     18.669 ms/op
     p(99.9900) =     30.447 ms/op
     p(99.9990) =     32.403 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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
# Warmup Iteration   1: 10.397 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.614 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
Iteration   1: 4.069 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.628 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  19.838 ms/op
                 listUser·p0.9999: 30.156 ms/op
                 listUser·p1.00:   30.933 ms/op

Iteration   2: 4.016 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 18.777 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 4.124 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  15.753 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235772
  mean =      4.069 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 224134 
    [ 5.000,  7.500) = 8019 
    [ 7.500, 10.000) = 2487 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      8.094 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     28.512 ms/op
     p(99.9990) =     30.523 ms/op
     p(99.9999) =     30.933 ms/op
    p(100.0000) =     30.933 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.180 ± 2.139  ops/ms
ClientPb.existUser                       thrpt       3   9.459 ± 2.901  ops/ms
ClientPb.getUser                         thrpt       3   9.416 ± 2.513  ops/ms
ClientPb.listUser                        thrpt       3   8.017 ± 3.473  ops/ms
ClientPb.createUser                       avgt       3   3.499 ± 1.482   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 1.042   ms/op
ClientPb.getUser                          avgt       3   3.371 ± 0.375   ms/op
ClientPb.listUser                         avgt       3   3.930 ± 1.072   ms/op
ClientPb.createUser                     sample  276648   3.467 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.317           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.776           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.732           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.702           ms/op
ClientPb.existUser                      sample  285183   3.364 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.288           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.508           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.261           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  278180   3.449 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.460           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.318           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.669           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.447           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.539           ms/op
ClientPb.listUser                       sample  235772   4.069 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.493           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.842           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.973           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.155           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.512           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.933           ms/op
