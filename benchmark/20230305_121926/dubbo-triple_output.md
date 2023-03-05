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
# Warmup Iteration   1: 1.637 ops/ms
# Warmup Iteration   2: 4.768 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 8.600 ops/ms
Iteration   2: 8.765 ops/ms
Iteration   3: 8.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.549 ±(99.9%) 4.484 ops/ms [Average]
  (min, avg, max) = (8.282, 8.549, 8.765), stdev = 0.246
  CI (99.9%): [4.065, 13.033] (assumes normal distribution)


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
# Warmup Iteration   1: 2.350 ops/ms
# Warmup Iteration   2: 6.919 ops/ms
# Warmup Iteration   3: 8.215 ops/ms
Iteration   1: 9.075 ops/ms
Iteration   2: 8.540 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.020 ±(99.9%) 8.304 ops/ms [Average]
  (min, avg, max) = (8.540, 9.020, 9.445), stdev = 0.455
  CI (99.9%): [0.716, 17.324] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.319 ops/ms
# Warmup Iteration   2: 6.838 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.588 ops/ms
Iteration   2: 8.754 ops/ms
Iteration   3: 8.827 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.723 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (8.588, 8.723, 8.827), stdev = 0.122
  CI (99.9%): [6.491, 10.956] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.523 ops/ms
# Warmup Iteration   2: 5.859 ops/ms
# Warmup Iteration   3: 6.926 ops/ms
Iteration   1: 7.000 ops/ms
Iteration   2: 7.457 ops/ms
Iteration   3: 7.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.289 ±(99.9%) 4.588 ops/ms [Average]
  (min, avg, max) = (7.000, 7.289, 7.457), stdev = 0.251
  CI (99.9%): [2.701, 11.877] (assumes normal distribution)


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
# Warmup Iteration   1: 12.131 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.014 ms/op
Iteration   1: 3.959 ±(99.9%) 0.010 ms/op
Iteration   2: 3.643 ±(99.9%) 0.015 ms/op
Iteration   3: 3.774 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.792 ±(99.9%) 2.896 ms/op [Average]
  (min, avg, max) = (3.643, 3.792, 3.959), stdev = 0.159
  CI (99.9%): [0.895, 6.688] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.903 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.814 ±(99.9%) 0.003 ms/op
Iteration   1: 3.768 ±(99.9%) 0.007 ms/op
Iteration   2: 3.629 ±(99.9%) 0.007 ms/op
Iteration   3: 3.800 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.733 ±(99.9%) 1.659 ms/op [Average]
  (min, avg, max) = (3.629, 3.733, 3.800), stdev = 0.091
  CI (99.9%): [2.074, 5.392] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.360 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.010 ms/op
Iteration   1: 4.027 ±(99.9%) 0.004 ms/op
Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
Iteration   3: 3.955 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.969 ±(99.9%) 0.968 ms/op [Average]
  (min, avg, max) = (3.923, 3.969, 4.027), stdev = 0.053
  CI (99.9%): [3.000, 4.937] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.282 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.568 ±(99.9%) 0.011 ms/op
Iteration   1: 4.361 ±(99.9%) 0.010 ms/op
Iteration   2: 4.324 ±(99.9%) 0.009 ms/op
Iteration   3: 4.208 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.298 ±(99.9%) 1.452 ms/op [Average]
  (min, avg, max) = (4.208, 4.298, 4.361), stdev = 0.080
  CI (99.9%): [2.846, 5.750] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.717 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 4.617 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.016 ms/op
Iteration   1: 3.752 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.853 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  21.093 ms/op
                 createUser·p0.9999: 26.426 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   2: 3.771 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.939 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.390 ms/op
                 createUser·p0.999:  14.752 ms/op
                 createUser·p0.9999: 28.099 ms/op
                 createUser·p1.00:   28.967 ms/op

Iteration   3: 3.981 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.729 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  27.448 ms/op
                 createUser·p0.9999: 34.406 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 250469
  mean =      3.832 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 647 
    [ 2.500,  5.000) = 238534 
    [ 5.000,  7.500) = 9711 
    [ 7.500, 10.000) = 1031 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     21.710 ms/op
     p(99.9900) =     32.834 ms/op
     p(99.9990) =     34.799 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.937 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.648 ±(99.9%) 0.011 ms/op
Iteration   1: 3.709 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  10.595 ms/op
                 existUser·p0.9999: 30.454 ms/op
                 existUser·p1.00:   31.097 ms/op

Iteration   2: 3.833 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.901 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.448 ms/op
                 existUser·p0.99:   7.627 ms/op
                 existUser·p0.999:  23.803 ms/op
                 existUser·p0.9999: 26.617 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 3.693 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.317 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  15.178 ms/op
                 existUser·p0.9999: 30.584 ms/op
                 existUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 256293
  mean =      3.744 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1186 
    [ 2.500,  5.000) = 244051 
    [ 5.000,  7.500) = 9464 
    [ 7.500, 10.000) = 1102 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      6.890 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     30.323 ms/op
     p(99.9990) =     32.049 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.584 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.259 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.013 ms/op
Iteration   1: 3.752 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.415 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.782 ms/op
                 getUser·p0.999:  21.168 ms/op
                 getUser·p0.9999: 24.559 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   2: 3.617 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.514 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  22.575 ms/op
                 getUser·p0.9999: 29.430 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   3: 3.710 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.554 ms/op
                 getUser·p0.999:  15.172 ms/op
                 getUser·p0.9999: 35.062 ms/op
                 getUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 259957
  mean =      3.692 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5074 
    [ 2.500,  5.000) = 241698 
    [ 5.000,  7.500) = 11198 
    [ 7.500, 10.000) = 1516 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     17.867 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.261 ±(99.9%) 0.173 ms/op
# Warmup Iteration   2: 4.731 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.525 ±(99.9%) 0.016 ms/op
Iteration   1: 4.224 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  23.812 ms/op
                 listUser·p0.9999: 28.508 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.222 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.137 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  15.733 ms/op
                 listUser·p0.9999: 19.904 ms/op
                 listUser·p1.00:   24.904 ms/op

Iteration   3: 4.448 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.698 ms/op
                 listUser·p0.9999: 23.575 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 223261
  mean =      4.295 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 210418 
    [ 5.000,  7.500) = 9732 
    [ 7.500, 10.000) = 2242 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 164 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      7.987 ms/op
     p(99.9000) =     16.965 ms/op
     p(99.9900) =     28.008 ms/op
     p(99.9990) =     28.813 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.549 ± 4.484  ops/ms
ClientPb.existUser                       thrpt       3   9.020 ± 8.304  ops/ms
ClientPb.getUser                         thrpt       3   8.723 ± 2.233  ops/ms
ClientPb.listUser                        thrpt       3   7.289 ± 4.588  ops/ms
ClientPb.createUser                       avgt       3   3.792 ± 2.896   ms/op
ClientPb.existUser                        avgt       3   3.733 ± 1.659   ms/op
ClientPb.getUser                          avgt       3   3.969 ± 0.968   ms/op
ClientPb.listUser                         avgt       3   4.298 ± 1.452   ms/op
ClientPb.createUser                     sample  250469   3.832 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.522           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.899           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.710           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.834           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.127           ms/op
ClientPb.existUser                      sample  256293   3.744 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.965           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.890           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.303           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.323           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.013           ms/op
ClientPb.getUser                        sample  259957   3.692 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.539           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.391           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.086           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.867           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.882           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.110           ms/op
ClientPb.listUser                       sample  223261   4.295 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.577           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.987           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.965           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.008           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
