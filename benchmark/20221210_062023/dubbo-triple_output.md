# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.705 ops/ms
# Warmup Iteration   2: 4.725 ops/ms
# Warmup Iteration   3: 8.299 ops/ms
Iteration   1: 9.040 ops/ms
Iteration   2: 9.008 ops/ms
Iteration   3: 9.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.075 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (9.008, 9.075, 9.176), stdev = 0.089
  CI (99.9%): [7.451, 10.698] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.791 ops/ms
# Warmup Iteration   2: 8.420 ops/ms
# Warmup Iteration   3: 9.031 ops/ms
Iteration   1: 9.598 ops/ms
Iteration   2: 9.698 ops/ms
Iteration   3: 9.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.597 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (9.495, 9.597, 9.698), stdev = 0.102
  CI (99.9%): [7.745, 11.449] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.550 ops/ms
# Warmup Iteration   2: 7.659 ops/ms
# Warmup Iteration   3: 9.025 ops/ms
Iteration   1: 8.633 ops/ms
Iteration   2: 8.931 ops/ms
Iteration   3: 9.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.912 ±(99.9%) 4.919 ops/ms [Average]
  (min, avg, max) = (8.633, 8.912, 9.171), stdev = 0.270
  CI (99.9%): [3.992, 13.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.495 ops/ms
# Warmup Iteration   2: 6.732 ops/ms
# Warmup Iteration   3: 7.602 ops/ms
Iteration   1: 7.725 ops/ms
Iteration   2: 7.684 ops/ms
Iteration   3: 7.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.788 ±(99.9%) 2.653 ops/ms [Average]
  (min, avg, max) = (7.684, 7.788, 7.954), stdev = 0.145
  CI (99.9%): [5.135, 10.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.805 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.010 ms/op
Iteration   1: 3.430 ±(99.9%) 0.006 ms/op
Iteration   2: 3.415 ±(99.9%) 0.006 ms/op
Iteration   3: 3.372 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.406 ±(99.9%) 0.553 ms/op [Average]
  (min, avg, max) = (3.372, 3.406, 3.430), stdev = 0.030
  CI (99.9%): [2.853, 3.958] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.533 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.008 ms/op
Iteration   1: 3.422 ±(99.9%) 0.008 ms/op
Iteration   2: 3.387 ±(99.9%) 0.007 ms/op
Iteration   3: 3.359 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.389 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.359, 3.389, 3.422), stdev = 0.031
  CI (99.9%): [2.819, 3.960] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.194 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.824 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.004 ms/op
Iteration   1: 3.450 ±(99.9%) 0.006 ms/op
Iteration   2: 3.497 ±(99.9%) 0.007 ms/op
Iteration   3: 3.412 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.453 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.412, 3.453, 3.497), stdev = 0.042
  CI (99.9%): [2.679, 4.227] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 13.564 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.008 ms/op
Iteration   1: 4.049 ±(99.9%) 0.012 ms/op
Iteration   2: 4.126 ±(99.9%) 0.014 ms/op
Iteration   3: 3.977 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.050 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (3.977, 4.050, 4.126), stdev = 0.075
  CI (99.9%): [2.690, 5.410] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 10.105 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
Iteration   1: 3.542 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.819 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  21.346 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   2: 3.417 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.735 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   26.870 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.378 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   5.822 ms/op
                 createUser·p0.999:  23.936 ms/op
                 createUser·p0.9999: 28.495 ms/op
                 createUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277327
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6144 
    [ 2.500,  5.000) = 266316 
    [ 5.000,  7.500) = 3787 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.378 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.814 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     26.610 ms/op
     p(99.9990) =     30.184 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.221 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.009 ms/op
Iteration   1: 3.399 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  21.507 ms/op
                 existUser·p0.9999: 25.725 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.558 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  23.364 ms/op
                 existUser·p0.9999: 27.034 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 3.360 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.986 ms/op
                 existUser·p0.999:  20.204 ms/op
                 existUser·p0.9999: 28.097 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279514
  mean =      3.437 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5294 
    [ 2.500,  5.000) = 267740 
    [ 5.000,  7.500) = 5202 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 108 
    [25.000, 27.500) = 119 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     20.757 ms/op
     p(99.9900) =     27.102 ms/op
     p(99.9990) =     28.541 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 11.033 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.012 ms/op
Iteration   1: 3.533 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   7.995 ms/op
                 getUser·p0.999:  21.231 ms/op
                 getUser·p0.9999: 29.196 ms/op
                 getUser·p1.00:   29.524 ms/op

Iteration   2: 3.406 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  22.907 ms/op
                 getUser·p0.9999: 25.881 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.946 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  19.661 ms/op
                 getUser·p0.9999: 26.801 ms/op
                 getUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275474
  mean =      3.483 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1617 
    [ 2.500,  5.000) = 267417 
    [ 5.000,  7.500) = 4228 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.990 ms/op
     p(99.9000) =     20.147 ms/op
     p(99.9900) =     27.996 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.524 ms/op
    p(100.0000) =     29.524 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.050 ±(99.9%) 0.184 ms/op
# Warmup Iteration   2: 4.460 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.362 ±(99.9%) 0.017 ms/op
Iteration   1: 4.033 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.778 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   4.728 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  24.576 ms/op
                 listUser·p0.9999: 28.840 ms/op
                 listUser·p1.00:   29.852 ms/op

Iteration   2: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.848 ms/op
                 listUser·p0.99:   7.330 ms/op
                 listUser·p0.999:  16.564 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.146 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 22.316 ms/op
                 listUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238806
  mean =      4.020 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 228553 
    [ 5.000,  7.500) = 8164 
    [ 7.500, 10.000) = 1293 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     17.302 ms/op
     p(99.9900) =     27.959 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.075 ± 1.624  ops/ms
ClientPb.existUser                       thrpt       3   9.597 ± 1.852  ops/ms
ClientPb.getUser                         thrpt       3   8.912 ± 4.919  ops/ms
ClientPb.listUser                        thrpt       3   7.788 ± 2.653  ops/ms
ClientPb.createUser                       avgt       3   3.406 ± 0.553   ms/op
ClientPb.existUser                        avgt       3   3.389 ± 0.571   ms/op
ClientPb.getUser                          avgt       3   3.453 ± 0.774   ms/op
ClientPb.listUser                         avgt       3   4.050 ± 1.360   ms/op
ClientPb.createUser                     sample  277327   3.458 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.378           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.814           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.627           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.610           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.769           ms/op
ClientPb.existUser                      sample  279514   3.437 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.923           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.985           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.757           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.102           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.574           ms/op
ClientPb.getUser                        sample  275474   3.483 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.059           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.990           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.147           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.996           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.524           ms/op
ClientPb.listUser                       sample  238806   4.020 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.561           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.959           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.852           ms/op
