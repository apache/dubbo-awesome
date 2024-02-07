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
# Warmup Iteration   1: 5.080 ops/ms
# Warmup Iteration   2: 11.902 ops/ms
# Warmup Iteration   3: 12.279 ops/ms
Iteration   1: 12.459 ops/ms
Iteration   2: 12.498 ops/ms
Iteration   3: 12.527 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.495 ±(99.9%) 0.631 ops/ms [Average]
  (min, avg, max) = (12.459, 12.495, 12.527), stdev = 0.035
  CI (99.9%): [11.864, 13.126] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.168 ops/ms
# Warmup Iteration   2: 13.021 ops/ms
# Warmup Iteration   3: 12.874 ops/ms
Iteration   1: 12.729 ops/ms
Iteration   2: 12.881 ops/ms
Iteration   3: 12.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.817 ±(99.9%) 1.435 ops/ms [Average]
  (min, avg, max) = (12.729, 12.817, 12.881), stdev = 0.079
  CI (99.9%): [11.382, 14.251] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.280 ops/ms
# Warmup Iteration   2: 12.521 ops/ms
# Warmup Iteration   3: 12.651 ops/ms
Iteration   1: 12.953 ops/ms
Iteration   2: 12.852 ops/ms
Iteration   3: 12.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.869 ±(99.9%) 1.406 ops/ms [Average]
  (min, avg, max) = (12.801, 12.869, 12.953), stdev = 0.077
  CI (99.9%): [11.463, 14.275] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.493 ops/ms
# Warmup Iteration   2: 10.486 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.547 ops/ms
Iteration   2: 10.424 ops/ms
Iteration   3: 10.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.477 ±(99.9%) 1.158 ops/ms [Average]
  (min, avg, max) = (10.424, 10.477, 10.547), stdev = 0.063
  CI (99.9%): [9.319, 11.635] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.004 ms/op
Iteration   1: 2.577 ±(99.9%) 0.004 ms/op
Iteration   2: 2.595 ±(99.9%) 0.004 ms/op
Iteration   3: 2.532 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.568 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (2.532, 2.568, 2.595), stdev = 0.033
  CI (99.9%): [1.971, 3.165] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.719 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.004 ms/op
Iteration   1: 2.457 ±(99.9%) 0.005 ms/op
Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.120 ms/op [Average]
  (min, avg, max) = (2.450, 2.457, 2.464), stdev = 0.007
  CI (99.9%): [2.337, 2.577] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.516 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
Iteration   3: 2.518 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.035 ms/op [Average]
  (min, avg, max) = (2.516, 2.518, 2.520), stdev = 0.002
  CI (99.9%): [2.483, 2.553] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.005 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
Iteration   3: 3.035 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (3.012, 3.028, 3.036), stdev = 0.013
  CI (99.9%): [2.783, 3.272] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.703 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.902 ms/op
                 createUser·p0.999:  11.634 ms/op
                 createUser·p0.9999: 14.303 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 2.563 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.035 ms/op
                 createUser·p0.999:  10.957 ms/op
                 createUser·p0.9999: 12.657 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  8.539 ms/op
                 createUser·p0.9999: 10.214 ms/op
                 createUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375307
  mean =      2.555 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 178780 
    [ 2.500,  3.750) = 191454 
    [ 3.750,  5.000) = 4054 
    [ 5.000,  6.250) = 543 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 140 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      3.940 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     13.221 ms/op
     p(99.9990) =     15.101 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  6.709 ms/op
                 existUser·p0.9999: 13.428 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   2: 2.493 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  5.751 ms/op
                 existUser·p0.9999: 13.225 ms/op
                 existUser·p1.00:   13.599 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.291 ms/op
                 existUser·p0.9999: 12.733 ms/op
                 existUser·p1.00:   12.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387155
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187964 
    [ 2.500,  3.750) = 196091 
    [ 3.750,  5.000) = 2200 
    [ 5.000,  6.250) = 460 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.592 ms/op
     p(99.9000) =      6.234 ms/op
     p(99.9900) =     13.063 ms/op
     p(99.9990) =     13.961 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 4.011 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  11.266 ms/op
                 getUser·p0.9999: 14.221 ms/op
                 getUser·p1.00:   14.860 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  6.494 ms/op
                 getUser·p0.9999: 14.060 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.920 ms/op
                 getUser·p0.999:  7.811 ms/op
                 getUser·p0.9999: 10.732 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384393
  mean =      2.495 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 190277 
    [ 2.500,  3.750) = 189758 
    [ 3.750,  5.000) = 3564 
    [ 5.000,  6.250) = 324 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      7.904 ms/op
     p(99.9900) =     13.746 ms/op
     p(99.9990) =     14.704 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.816 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.114 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.008 ms/op
Iteration   1: 3.079 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.029 ms/op
                 listUser·p0.50:   3.023 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.486 ms/op
                 listUser·p0.9999: 11.061 ms/op
                 listUser·p1.00:   12.222 ms/op

Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.470 ms/op
                 listUser·p0.9999: 10.676 ms/op
                 listUser·p1.00:   12.091 ms/op

Iteration   3: 3.071 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.888 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.300 ms/op
                 listUser·p0.9999: 11.462 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 311893
  mean =      3.075 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 79999 
    [ 2.500,  3.750) = 188945 
    [ 3.750,  5.000) = 35214 
    [ 5.000,  6.250) = 6176 
    [ 6.250,  7.500) = 690 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 393 
    [10.000, 11.250) = 140 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     11.285 ms/op
     p(99.9990) =     12.082 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.495 ± 0.631  ops/ms
ClientPb.existUser                       thrpt       3  12.817 ± 1.435  ops/ms
ClientPb.getUser                         thrpt       3  12.869 ± 1.406  ops/ms
ClientPb.listUser                        thrpt       3  10.477 ± 1.158  ops/ms
ClientPb.createUser                       avgt       3   2.568 ± 0.597   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.120   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.035   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.244   ms/op
ClientPb.createUser                     sample  375307   2.555 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.899           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.236           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.634           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.221           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.352           ms/op
ClientPb.existUser                      sample  387155   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.866           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.234           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.063           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.156           ms/op
ClientPb.getUser                        sample  384393   2.495 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.916           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.904           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.746           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.860           ms/op
ClientPb.listUser                       sample  311893   3.075 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.859           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.019           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.285           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.222           ms/op
