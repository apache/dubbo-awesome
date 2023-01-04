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
# Warmup Iteration   1: 2.815 ops/ms
# Warmup Iteration   2: 7.231 ops/ms
# Warmup Iteration   3: 10.092 ops/ms
Iteration   1: 8.910 ops/ms
Iteration   2: 9.307 ops/ms
Iteration   3: 9.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.213 ±(99.9%) 4.905 ops/ms [Average]
  (min, avg, max) = (8.910, 9.213, 9.422), stdev = 0.269
  CI (99.9%): [4.308, 14.119] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 9.020 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 10.560 ops/ms
Iteration   3: 10.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.405 ±(99.9%) 3.220 ops/ms [Average]
  (min, avg, max) = (10.213, 10.405, 10.560), stdev = 0.177
  CI (99.9%): [7.185, 13.626] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.793 ops/ms
# Warmup Iteration   2: 8.751 ops/ms
# Warmup Iteration   3: 8.969 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.753 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.592 ±(99.9%) 2.951 ops/ms [Average]
  (min, avg, max) = (9.430, 9.592, 9.753), stdev = 0.162
  CI (99.9%): [6.641, 12.543] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.176 ops/ms
# Warmup Iteration   2: 7.625 ops/ms
# Warmup Iteration   3: 8.472 ops/ms
Iteration   1: 8.879 ops/ms
Iteration   2: 9.039 ops/ms
Iteration   3: 8.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.902 ±(99.9%) 2.318 ops/ms [Average]
  (min, avg, max) = (8.788, 8.902, 9.039), stdev = 0.127
  CI (99.9%): [6.584, 11.220] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.234 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.005 ms/op
Iteration   1: 3.098 ±(99.9%) 0.009 ms/op
Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
Iteration   3: 3.037 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.094 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.037, 3.094, 3.147), stdev = 0.055
  CI (99.9%): [2.087, 4.101] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 6.684 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.899 ±(99.9%) 0.011 ms/op
Iteration   1: 3.067 ±(99.9%) 0.005 ms/op
Iteration   2: 2.921 ±(99.9%) 0.007 ms/op
Iteration   3: 2.901 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.963 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (2.901, 2.963, 3.067), stdev = 0.090
  CI (99.9%): [1.316, 4.611] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.211 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
Iteration   1: 3.116 ±(99.9%) 0.004 ms/op
Iteration   2: 3.053 ±(99.9%) 0.010 ms/op
Iteration   3: 3.145 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.105 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.053, 3.105, 3.145), stdev = 0.047
  CI (99.9%): [2.249, 3.960] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 9.671 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
Iteration   1: 3.605 ±(99.9%) 0.013 ms/op
Iteration   2: 3.640 ±(99.9%) 0.017 ms/op
Iteration   3: 3.761 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.669 ±(99.9%) 1.491 ms/op [Average]
  (min, avg, max) = (3.605, 3.669, 3.761), stdev = 0.082
  CI (99.9%): [2.177, 5.160] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.767 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.010 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.396 ms/op
                 createUser·p0.99:   4.940 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 21.299 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 3.107 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.466 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.967 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  12.712 ms/op
                 createUser·p0.9999: 24.763 ms/op
                 createUser·p1.00:   24.969 ms/op

Iteration   3: 3.185 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.300 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.547 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  18.140 ms/op
                 createUser·p0.9999: 28.108 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 309126
  mean =      3.103 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19732 
    [ 2.500,  5.000) = 285214 
    [ 5.000,  7.500) = 3287 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =     17.854 ms/op
     p(99.9900) =     27.329 ms/op
     p(99.9990) =     30.191 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.284 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.009 ms/op
Iteration   1: 3.170 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.456 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  10.526 ms/op
                 existUser·p0.9999: 36.897 ms/op
                 existUser·p1.00:   38.470 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  10.783 ms/op
                 existUser·p0.9999: 26.313 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   3: 3.324 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  17.329 ms/op
                 existUser·p0.9999: 24.536 ms/op
                 existUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302581
  mean =      3.170 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17588 
    [ 2.500,  5.000) = 280331 
    [ 5.000,  7.500) = 3870 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 128 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     13.577 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     37.613 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.908 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.311 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.010 ms/op
Iteration   1: 3.079 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.782 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.371 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  12.602 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   32.604 ms/op

Iteration   2: 3.113 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.503 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  10.029 ms/op
                 getUser·p0.9999: 24.281 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  9.994 ms/op
                 getUser·p0.9999: 22.601 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 312667
  mean =      3.067 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12097 
    [ 2.500,  5.000) = 294652 
    [ 5.000,  7.500) = 5101 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.513 ms/op
     p(99.9900) =     30.105 ms/op
     p(99.9990) =     32.534 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.032 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.011 ms/op
Iteration   1: 3.555 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.400 ms/op
                 listUser·p0.90:   3.970 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 20.709 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.577 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   3.441 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 16.435 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.739 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.876 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 21.525 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 265000
  mean =      3.622 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 236 
    [ 2.500,  5.000) = 257480 
    [ 5.000,  7.500) = 5552 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 240 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     15.516 ms/op
     p(99.9900) =     21.086 ms/op
     p(99.9990) =     21.933 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.213 ± 4.905  ops/ms
ClientPb.existUser                       thrpt       3  10.405 ± 3.220  ops/ms
ClientPb.getUser                         thrpt       3   9.592 ± 2.951  ops/ms
ClientPb.listUser                        thrpt       3   8.902 ± 2.318  ops/ms
ClientPb.createUser                       avgt       3   3.094 ± 1.007   ms/op
ClientPb.existUser                        avgt       3   2.963 ± 1.647   ms/op
ClientPb.getUser                          avgt       3   3.105 ± 0.855   ms/op
ClientPb.listUser                         avgt       3   3.669 ± 1.491   ms/op
ClientPb.createUser                     sample  309126   3.103 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.300           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.202           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.854           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.329           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.031           ms/op
ClientPb.existUser                      sample  302581   3.170 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.395           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.568           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.439           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.577           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.110           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.470           ms/op
ClientPb.getUser                        sample  312667   3.067 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.782           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.945           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.538           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.513           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.105           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.604           ms/op
ClientPb.listUser                       sample  265000   3.622 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.683           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.478           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.086           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.643           ms/op
