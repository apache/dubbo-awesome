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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.886 ops/ms
# Warmup Iteration   3: 8.686 ops/ms
Iteration   1: 9.332 ops/ms
Iteration   2: 9.086 ops/ms
Iteration   3: 9.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.316 ±(99.9%) 4.067 ops/ms [Average]
  (min, avg, max) = (9.086, 9.316, 9.531), stdev = 0.223
  CI (99.9%): [5.249, 13.383] (assumes normal distribution)


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
# Warmup Iteration   1: 3.438 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 9.223 ops/ms
Iteration   1: 9.946 ops/ms
Iteration   2: 9.535 ops/ms
Iteration   3: 10.085 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.855 ±(99.9%) 5.215 ops/ms [Average]
  (min, avg, max) = (9.535, 9.855, 10.085), stdev = 0.286
  CI (99.9%): [4.640, 15.071] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 8.519 ops/ms
# Warmup Iteration   3: 9.402 ops/ms
Iteration   1: 9.383 ops/ms
Iteration   2: 9.694 ops/ms
Iteration   3: 9.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.593 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (9.383, 9.593, 9.701), stdev = 0.181
  CI (99.9%): [6.283, 12.903] (assumes normal distribution)


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
# Warmup Iteration   1: 2.996 ops/ms
# Warmup Iteration   2: 7.149 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 7.814 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.029 ±(99.9%) 4.410 ops/ms [Average]
  (min, avg, max) = (7.814, 8.029, 8.291), stdev = 0.242
  CI (99.9%): [3.619, 12.439] (assumes normal distribution)


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
# Warmup Iteration   1: 9.366 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.006 ms/op
Iteration   1: 3.493 ±(99.9%) 0.006 ms/op
Iteration   2: 3.449 ±(99.9%) 0.004 ms/op
Iteration   3: 3.432 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.458 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.432, 3.458, 3.493), stdev = 0.032
  CI (99.9%): [2.877, 4.039] (assumes normal distribution)


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
# Warmup Iteration   1: 8.954 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 3.656 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.005 ms/op
Iteration   1: 3.407 ±(99.9%) 0.008 ms/op
Iteration   2: 3.320 ±(99.9%) 0.004 ms/op
Iteration   3: 3.256 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.328 ±(99.9%) 1.383 ms/op [Average]
  (min, avg, max) = (3.256, 3.328, 3.407), stdev = 0.076
  CI (99.9%): [1.944, 4.711] (assumes normal distribution)


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
# Warmup Iteration   1: 10.284 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.004 ms/op
Iteration   1: 3.432 ±(99.9%) 0.003 ms/op
Iteration   2: 3.336 ±(99.9%) 0.006 ms/op
Iteration   3: 3.507 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.425 ±(99.9%) 1.567 ms/op [Average]
  (min, avg, max) = (3.336, 3.425, 3.507), stdev = 0.086
  CI (99.9%): [1.858, 4.992] (assumes normal distribution)


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
# Warmup Iteration   1: 11.432 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.946 ±(99.9%) 0.010 ms/op
Iteration   1: 3.931 ±(99.9%) 0.012 ms/op
Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
Iteration   3: 3.995 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.950 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.924, 3.950, 3.995), stdev = 0.039
  CI (99.9%): [3.238, 4.662] (assumes normal distribution)


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
# Warmup Iteration   1: 9.791 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.012 ms/op
Iteration   1: 3.351 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  20.969 ms/op
                 createUser·p0.9999: 23.590 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.604 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.619 ms/op
                 createUser·p0.999:  24.158 ms/op
                 createUser·p0.9999: 27.427 ms/op
                 createUser·p1.00:   28.770 ms/op

Iteration   3: 3.406 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.657 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.661 ms/op
                 createUser·p0.999:  17.108 ms/op
                 createUser·p0.9999: 26.341 ms/op
                 createUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278061
  mean =      3.450 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10635 
    [ 2.500,  5.000) = 260913 
    [ 5.000,  7.500) = 5718 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 86 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     17.299 ms/op
     p(99.9900) =     26.870 ms/op
     p(99.9990) =     27.938 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 8.645 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.010 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.595 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.975 ms/op
                 existUser·p0.99:   6.207 ms/op
                 existUser·p0.999:  20.852 ms/op
                 existUser·p0.9999: 28.256 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   2: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  21.135 ms/op
                 existUser·p0.9999: 28.560 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   3: 3.312 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.738 ms/op
                 existUser·p0.999:  8.536 ms/op
                 existUser·p0.9999: 26.619 ms/op
                 existUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286270
  mean =      3.351 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8474 
    [ 2.500,  5.000) = 272570 
    [ 5.000,  7.500) = 4475 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 91 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     10.255 ms/op
     p(99.9900) =     28.160 ms/op
     p(99.9990) =     28.890 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 9.451 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.010 ms/op
Iteration   1: 3.448 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.700 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  20.809 ms/op
                 getUser·p0.9999: 24.632 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 3.489 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  21.932 ms/op
                 getUser·p0.9999: 26.356 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.348 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  18.332 ms/op
                 getUser·p0.9999: 31.668 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280191
  mean =      3.427 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9278 
    [ 2.500,  5.000) = 264360 
    [ 5.000,  7.500) = 5360 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     19.046 ms/op
     p(99.9900) =     30.636 ms/op
     p(99.9990) =     32.807 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 11.864 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.889 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.014 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.842 ms/op
                 listUser·p0.999:  20.753 ms/op
                 listUser·p0.9999: 24.707 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.589 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.420 ms/op
                 listUser·p0.999:  17.504 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   3: 4.058 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  15.797 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236308
  mean =      4.062 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 227762 
    [ 5.000,  7.500) = 6103 
    [ 7.500, 10.000) = 1536 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 185 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.316 ± 4.067  ops/ms
ClientPb.existUser                       thrpt       3   9.855 ± 5.215  ops/ms
ClientPb.getUser                         thrpt       3   9.593 ± 3.310  ops/ms
ClientPb.listUser                        thrpt       3   8.029 ± 4.410  ops/ms
ClientPb.createUser                       avgt       3   3.458 ± 0.581   ms/op
ClientPb.existUser                        avgt       3   3.328 ± 1.383   ms/op
ClientPb.getUser                          avgt       3   3.425 ± 1.567   ms/op
ClientPb.listUser                         avgt       3   3.950 ± 0.712   ms/op
ClientPb.createUser                     sample  278061   3.450 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.516           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.299           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.870           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.770           ms/op
ClientPb.existUser                      sample  286270   3.351 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.255           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.160           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.262           ms/op
ClientPb.getUser                        sample  280191   3.427 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.548           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.046           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.636           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  236308   4.062 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.862           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.936           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.170           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.101           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.428           ms/op
