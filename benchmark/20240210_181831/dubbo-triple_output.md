# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.282 ops/ms
# Warmup Iteration   2: 12.303 ops/ms
# Warmup Iteration   3: 12.612 ops/ms
Iteration   1: 12.788 ops/ms
Iteration   2: 12.833 ops/ms
Iteration   3: 12.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.808 ±(99.9%) 0.416 ops/ms [Average]
  (min, avg, max) = (12.788, 12.808, 12.833), stdev = 0.023
  CI (99.9%): [12.392, 13.225] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 13.043 ops/ms
# Warmup Iteration   3: 13.068 ops/ms
Iteration   1: 13.039 ops/ms
Iteration   2: 13.036 ops/ms
Iteration   3: 13.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.036 ±(99.9%) 0.043 ops/ms [Average]
  (min, avg, max) = (13.034, 13.036, 13.039), stdev = 0.002
  CI (99.9%): [12.993, 13.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.245 ops/ms
# Warmup Iteration   2: 12.716 ops/ms
# Warmup Iteration   3: 13.028 ops/ms
Iteration   1: 12.960 ops/ms
Iteration   2: 12.969 ops/ms
Iteration   3: 12.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.959 ±(99.9%) 0.185 ops/ms [Average]
  (min, avg, max) = (12.948, 12.959, 12.969), stdev = 0.010
  CI (99.9%): [12.774, 13.144] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.934 ops/ms
# Warmup Iteration   2: 10.777 ops/ms
# Warmup Iteration   3: 10.820 ops/ms
Iteration   1: 10.901 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.794 ±(99.9%) 1.938 ops/ms [Average]
  (min, avg, max) = (10.689, 10.794, 10.901), stdev = 0.106
  CI (99.9%): [8.857, 12.732] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.021 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.497 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.098 ms/op [Average]
  (min, avg, max) = (2.487, 2.491, 2.497), stdev = 0.005
  CI (99.9%): [2.393, 2.590] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.557 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.003 ms/op
Iteration   1: 2.420 ±(99.9%) 0.004 ms/op
Iteration   2: 2.431 ±(99.9%) 0.003 ms/op
Iteration   3: 2.425 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.425 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.420, 2.425, 2.431), stdev = 0.005
  CI (99.9%): [2.326, 2.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.472 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.482 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (2.472, 2.482, 2.498), stdev = 0.014
  CI (99.9%): [2.223, 2.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.550 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.006 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 2.996 ±(99.9%) 0.005 ms/op
Iteration   3: 3.010 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.160 ms/op [Average]
  (min, avg, max) = (2.996, 3.006, 3.012), stdev = 0.009
  CI (99.9%): [2.846, 3.166] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.096 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.637 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  10.826 ms/op
                 createUser·p0.9999: 13.107 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  9.432 ms/op
                 createUser·p0.9999: 12.700 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.650 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 11.485 ms/op
                 createUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383869
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 186355 
    [ 2.500,  3.750) = 194027 
    [ 3.750,  5.000) = 2639 
    [ 5.000,  6.250) = 335 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 141 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.718 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.604 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.425 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.005 ms/op
Iteration   1: 2.423 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  5.903 ms/op
                 existUser·p0.9999: 13.202 ms/op
                 existUser·p1.00:   13.910 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.929 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.592 ms/op
                 existUser·p0.999:  7.752 ms/op
                 existUser·p0.9999: 11.515 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   3: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.850 ms/op
                 existUser·p0.999:  8.480 ms/op
                 existUser·p0.9999: 12.142 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393722
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 194207 
    [ 2.500,  3.750) = 196213 
    [ 3.750,  5.000) = 2409 
    [ 5.000,  6.250) = 370 
    [ 6.250,  7.500) = 77 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 109 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.641 ms/op
     p(99.9000) =      7.852 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     13.521 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.766 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.519 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  10.043 ms/op
                 getUser·p0.9999: 14.261 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.088 ms/op
                 getUser·p0.99:   3.555 ms/op
                 getUser·p0.999:  6.289 ms/op
                 getUser·p0.9999: 12.616 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  7.859 ms/op
                 getUser·p0.9999: 11.715 ms/op
                 getUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386294
  mean =      2.483 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 192434 
    [ 2.500,  3.750) = 188780 
    [ 3.750,  5.000) = 3855 
    [ 5.000,  6.250) = 718 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 99 
    [11.250, 12.500) = 138 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =      7.587 ms/op
     p(99.9900) =     12.786 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.524 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.618 ms/op
                 listUser·p0.9999: 10.623 ms/op
                 listUser·p1.00:   10.912 ms/op

Iteration   2: 3.043 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.671 ms/op
                 listUser·p0.50:   2.982 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.650 ms/op
                 listUser·p0.9999: 10.985 ms/op
                 listUser·p1.00:   11.387 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 11.918 ms/op
                 listUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317052
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 87248 
    [ 2.500,  3.750) = 190127 
    [ 3.750,  5.000) = 32635 
    [ 5.000,  6.250) = 5735 
    [ 6.250,  7.500) = 578 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 232 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.175 ms/op
     p(99.9900) =     11.397 ms/op
     p(99.9990) =     12.433 ms/op
     p(99.9999) =     13.042 ms/op
    p(100.0000) =     13.042 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.808 ± 0.416  ops/ms
ClientPb.existUser                       thrpt       3  13.036 ± 0.043  ops/ms
ClientPb.getUser                         thrpt       3  12.959 ± 0.185  ops/ms
ClientPb.listUser                        thrpt       3  10.794 ± 1.938  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.098   ms/op
ClientPb.existUser                        avgt       3   2.425 ± 0.099   ms/op
ClientPb.getUser                          avgt       3   2.482 ± 0.259   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.160   ms/op
ClientPb.createUser                     sample  383869   2.498 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.718           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  393722   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.870           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.949           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.852           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.894           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.910           ms/op
ClientPb.getUser                        sample  386294   2.483 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.787           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.019           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.916           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.587           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.786           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  317052   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.671           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.961           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.175           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.397           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.042           ms/op
