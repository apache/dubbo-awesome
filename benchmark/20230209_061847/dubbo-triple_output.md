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
# Warmup Iteration   1: 2.144 ops/ms
# Warmup Iteration   2: 5.427 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 8.876 ops/ms
Iteration   2: 9.193 ops/ms
Iteration   3: 9.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.084 ±(99.9%) 3.289 ops/ms [Average]
  (min, avg, max) = (8.876, 9.084, 9.193), stdev = 0.180
  CI (99.9%): [5.794, 12.373] (assumes normal distribution)


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
# Warmup Iteration   1: 2.753 ops/ms
# Warmup Iteration   2: 8.382 ops/ms
# Warmup Iteration   3: 9.524 ops/ms
Iteration   1: 9.520 ops/ms
Iteration   2: 9.394 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.447 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (9.394, 9.447, 9.520), stdev = 0.066
  CI (99.9%): [8.247, 10.646] (assumes normal distribution)


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
# Warmup Iteration   1: 3.246 ops/ms
# Warmup Iteration   2: 8.328 ops/ms
# Warmup Iteration   3: 8.975 ops/ms
Iteration   1: 9.138 ops/ms
Iteration   2: 9.502 ops/ms
Iteration   3: 9.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.324 ±(99.9%) 3.328 ops/ms [Average]
  (min, avg, max) = (9.138, 9.324, 9.502), stdev = 0.182
  CI (99.9%): [5.996, 12.653] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.770 ops/ms
# Warmup Iteration   2: 7.286 ops/ms
# Warmup Iteration   3: 7.594 ops/ms
Iteration   1: 7.781 ops/ms
Iteration   2: 7.856 ops/ms
Iteration   3: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.867 ±(99.9%) 1.682 ops/ms [Average]
  (min, avg, max) = (7.781, 7.867, 7.965), stdev = 0.092
  CI (99.9%): [6.185, 9.549] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.833 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.010 ms/op
Iteration   1: 3.487 ±(99.9%) 0.013 ms/op
Iteration   2: 3.467 ±(99.9%) 0.010 ms/op
Iteration   3: 3.483 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.479 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (3.467, 3.479, 3.487), stdev = 0.011
  CI (99.9%): [3.284, 3.674] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 10.385 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.397 ±(99.9%) 0.009 ms/op
Iteration   1: 3.341 ±(99.9%) 0.006 ms/op
Iteration   2: 3.206 ±(99.9%) 0.010 ms/op
Iteration   3: 3.253 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 1.245 ms/op [Average]
  (min, avg, max) = (3.206, 3.267, 3.341), stdev = 0.068
  CI (99.9%): [2.022, 4.511] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.302 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.009 ms/op
Iteration   1: 3.350 ±(99.9%) 0.011 ms/op
Iteration   2: 3.382 ±(99.9%) 0.007 ms/op
Iteration   3: 3.385 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.373 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.350, 3.373, 3.385), stdev = 0.019
  CI (99.9%): [3.018, 3.727] (assumes normal distribution)


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
# Warmup Iteration   1: 11.242 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.008 ms/op
Iteration   1: 4.063 ±(99.9%) 0.008 ms/op
Iteration   2: 3.994 ±(99.9%) 0.015 ms/op
Iteration   3: 3.948 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.002 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.948, 4.002, 4.063), stdev = 0.058
  CI (99.9%): [2.951, 5.053] (assumes normal distribution)


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
# Warmup Iteration   1: 9.849 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.500 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.398 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  22.251 ms/op
                 createUser·p0.9999: 26.078 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.520 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.251 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  20.814 ms/op
                 createUser·p0.9999: 32.834 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274766
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7940 
    [ 2.500,  5.000) = 261004 
    [ 5.000,  7.500) = 4731 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     20.684 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     33.588 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 8.923 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.009 ms/op
Iteration   1: 3.237 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.357 ms/op
                 existUser·p0.999:  10.273 ms/op
                 existUser·p0.9999: 23.285 ms/op
                 existUser·p1.00:   23.822 ms/op

Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.291 ms/op
                 existUser·p0.999:  11.583 ms/op
                 existUser·p0.9999: 27.010 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   3: 3.431 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.709 ms/op
                 existUser·p0.999:  24.348 ms/op
                 existUser·p0.9999: 33.927 ms/op
                 existUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290613
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5365 
    [ 2.500,  5.000) = 279604 
    [ 5.000,  7.500) = 4747 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.823 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     30.671 ms/op
     p(99.9990) =     35.402 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 8.515 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.767 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.012 ms/op
Iteration   1: 3.542 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  22.405 ms/op
                 getUser·p0.9999: 24.935 ms/op
                 getUser·p1.00:   25.788 ms/op

Iteration   2: 3.402 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  24.137 ms/op
                 getUser·p0.9999: 26.378 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.415 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.407 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   6.064 ms/op
                 getUser·p0.999:  12.341 ms/op
                 getUser·p0.9999: 27.021 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278387
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5150 
    [ 2.500,  5.000) = 263944 
    [ 5.000,  7.500) = 7931 
    [ 7.500, 10.000) = 923 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 96 

  Percentiles, ms/op:
      p(0.0000) =      1.407 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     12.764 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     28.660 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


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
# Warmup Iteration   1: 10.921 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.013 ms/op
Iteration   1: 4.167 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  21.207 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   8.061 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 23.652 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   3: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  17.172 ms/op
                 listUser·p0.9999: 21.398 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235278
  mean =      4.082 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 225558 
    [ 5.000,  7.500) = 6741 
    [ 7.500, 10.000) = 1903 
    [10.000, 12.500) = 534 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     23.969 ms/op
     p(99.9990) =     25.203 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.084 ± 3.289  ops/ms
ClientPb.existUser                       thrpt       3   9.447 ± 1.200  ops/ms
ClientPb.getUser                         thrpt       3   9.324 ± 3.328  ops/ms
ClientPb.listUser                        thrpt       3   7.867 ± 1.682  ops/ms
ClientPb.createUser                       avgt       3   3.479 ± 0.195   ms/op
ClientPb.existUser                        avgt       3   3.267 ± 1.245   ms/op
ClientPb.getUser                          avgt       3   3.373 ± 0.354   ms/op
ClientPb.listUser                         avgt       3   4.002 ± 1.051   ms/op
ClientPb.createUser                     sample  274766   3.493 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.398           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.684           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.145           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  290613   3.301 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.621           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.823           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.567           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.671           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.979           ms/op
ClientPb.getUser                        sample  278387   3.452 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.407           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.832           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.764           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.378           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.803           ms/op
ClientPb.listUser                       sample  235278   4.082 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.792           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.971           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.088           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.969           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.362           ms/op
