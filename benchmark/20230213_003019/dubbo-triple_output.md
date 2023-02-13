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
# Warmup Iteration   1: 2.649 ops/ms
# Warmup Iteration   2: 6.279 ops/ms
# Warmup Iteration   3: 9.011 ops/ms
Iteration   1: 9.611 ops/ms
Iteration   2: 9.718 ops/ms
Iteration   3: 9.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.662 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (9.611, 9.662, 9.718), stdev = 0.053
  CI (99.9%): [8.688, 10.637] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.883 ops/ms
# Warmup Iteration   2: 9.581 ops/ms
# Warmup Iteration   3: 9.746 ops/ms
Iteration   1: 9.999 ops/ms
Iteration   2: 9.827 ops/ms
Iteration   3: 10.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.000 ±(99.9%) 3.179 ops/ms [Average]
  (min, avg, max) = (9.827, 10.000, 10.176), stdev = 0.174
  CI (99.9%): [6.821, 13.180] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.600 ops/ms
# Warmup Iteration   2: 9.278 ops/ms
# Warmup Iteration   3: 9.752 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.411 ops/ms
Iteration   3: 9.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.088 ±(99.9%) 5.722 ops/ms [Average]
  (min, avg, max) = (9.785, 10.088, 10.411), stdev = 0.314
  CI (99.9%): [4.366, 15.810] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.494 ops/ms
# Warmup Iteration   2: 8.026 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 8.680 ops/ms
Iteration   2: 8.431 ops/ms
Iteration   3: 8.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.550 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (8.431, 8.550, 8.680), stdev = 0.125
  CI (99.9%): [6.267, 10.832] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.663 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.004 ms/op
Iteration   1: 3.075 ±(99.9%) 0.005 ms/op
Iteration   2: 3.201 ±(99.9%) 0.010 ms/op
Iteration   3: 3.146 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.141 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (3.075, 3.141, 3.201), stdev = 0.063
  CI (99.9%): [1.987, 4.295] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.360 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.245 ±(99.9%) 0.005 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
Iteration   2: 3.114 ±(99.9%) 0.008 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.120 ±(99.9%) 1.086 ms/op [Average]
  (min, avg, max) = (3.063, 3.120, 3.182), stdev = 0.060
  CI (99.9%): [2.034, 4.206] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 7.896 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.373 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.003 ms/op
Iteration   1: 3.236 ±(99.9%) 0.007 ms/op
Iteration   2: 3.366 ±(99.9%) 0.004 ms/op
Iteration   3: 3.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.341 ±(99.9%) 1.745 ms/op [Average]
  (min, avg, max) = (3.236, 3.341, 3.422), stdev = 0.096
  CI (99.9%): [1.597, 5.086] (assumes normal distribution)


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
# Warmup Iteration   1: 8.573 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.005 ms/op
Iteration   1: 3.762 ±(99.9%) 0.008 ms/op
Iteration   2: 4.002 ±(99.9%) 0.006 ms/op
Iteration   3: 3.696 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.820 ±(99.9%) 2.941 ms/op [Average]
  (min, avg, max) = (3.696, 3.820, 4.002), stdev = 0.161
  CI (99.9%): [0.879, 6.761] (assumes normal distribution)


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
# Warmup Iteration   1: 8.334 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.010 ms/op
Iteration   1: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.774 ms/op
                 createUser·p0.999:  12.093 ms/op
                 createUser·p0.9999: 21.274 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 3.181 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  14.162 ms/op
                 createUser·p0.9999: 23.722 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 25.561 ms/op
                 createUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298823
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22455 
    [ 2.500,  5.000) = 270963 
    [ 5.000,  7.500) = 4524 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     23.601 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 7.450 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.008 ms/op
Iteration   1: 3.029 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.808 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  8.428 ms/op
                 existUser·p0.9999: 22.770 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   2: 3.104 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  10.501 ms/op
                 existUser·p0.9999: 21.846 ms/op
                 existUser·p1.00:   23.036 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.969 ms/op
                 existUser·p0.9999: 20.677 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314151
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11269 
    [ 2.500,  5.000) = 298734 
    [ 5.000,  7.500) = 3663 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      5.235 ms/op
     p(99.9000) =     10.642 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     22.998 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 7.662 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.008 ms/op
Iteration   1: 3.350 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.922 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  17.970 ms/op
                 getUser·p0.9999: 24.099 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.402 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  18.514 ms/op
                 getUser·p0.9999: 20.466 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   3: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.895 ms/op
                 getUser·p0.999:  14.534 ms/op
                 getUser·p0.9999: 20.444 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290667
  mean =      3.304 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14263 
    [ 2.500,  5.000) = 264700 
    [ 5.000,  7.500) = 10525 
    [ 7.500, 10.000) = 719 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     15.958 ms/op
     p(99.9900) =     23.549 ms/op
     p(99.9990) =     24.508 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 8.876 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.012 ms/op
Iteration   1: 3.746 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  15.158 ms/op
                 listUser·p0.9999: 18.725 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   2: 3.763 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 13.451 ms/op
                 listUser·p1.00:   14.008 ms/op

Iteration   3: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.905 ms/op
                 listUser·p0.9999: 19.546 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255573
  mean =      3.754 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 247504 
    [ 5.000,  7.500) = 6316 
    [ 7.500, 10.000) = 1045 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     13.393 ms/op
     p(99.9900) =     18.743 ms/op
     p(99.9990) =     20.167 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.662 ± 0.974  ops/ms
ClientPb.existUser                       thrpt       3  10.000 ± 3.179  ops/ms
ClientPb.getUser                         thrpt       3  10.088 ± 5.722  ops/ms
ClientPb.listUser                        thrpt       3   8.550 ± 2.282  ops/ms
ClientPb.createUser                       avgt       3   3.141 ± 1.154   ms/op
ClientPb.existUser                        avgt       3   3.120 ± 1.086   ms/op
ClientPb.getUser                          avgt       3   3.341 ± 1.745   ms/op
ClientPb.listUser                         avgt       3   3.820 ± 2.941   ms/op
ClientPb.createUser                     sample  298823   3.213 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.007           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.601           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.051           ms/op
ClientPb.existUser                      sample  314151   3.054 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.808           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.642           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.086           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.036           ms/op
ClientPb.getUser                        sample  290667   3.304 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.521           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.170           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.514           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.562           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.958           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.549           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.871           ms/op
ClientPb.listUser                       sample  255573   3.754 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.021           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.145           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.393           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.743           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.316           ms/op
