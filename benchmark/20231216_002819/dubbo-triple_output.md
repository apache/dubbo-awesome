# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.650 ops/ms
# Warmup Iteration   2: 11.936 ops/ms
# Warmup Iteration   3: 12.413 ops/ms
Iteration   1: 12.503 ops/ms
Iteration   2: 12.550 ops/ms
Iteration   3: 12.638 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.564 ±(99.9%) 1.254 ops/ms [Average]
  (min, avg, max) = (12.503, 12.564, 12.638), stdev = 0.069
  CI (99.9%): [11.309, 13.818] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.069 ops/ms
# Warmup Iteration   2: 13.149 ops/ms
# Warmup Iteration   3: 13.047 ops/ms
Iteration   1: 13.131 ops/ms
Iteration   2: 13.133 ops/ms
Iteration   3: 12.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.075 ±(99.9%) 1.784 ops/ms [Average]
  (min, avg, max) = (12.963, 13.075, 13.133), stdev = 0.098
  CI (99.9%): [11.292, 14.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.807 ops/ms
# Warmup Iteration   2: 12.286 ops/ms
# Warmup Iteration   3: 12.513 ops/ms
Iteration   1: 12.424 ops/ms
Iteration   2: 12.572 ops/ms
Iteration   3: 12.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.506 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (12.424, 12.506, 12.572), stdev = 0.076
  CI (99.9%): [11.127, 13.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.480 ops/ms
# Warmup Iteration   2: 10.347 ops/ms
# Warmup Iteration   3: 10.325 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.428 ops/ms
Iteration   3: 10.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.367 ±(99.9%) 2.173 ops/ms [Average]
  (min, avg, max) = (10.230, 10.367, 10.443), stdev = 0.119
  CI (99.9%): [8.194, 12.540] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.003 ms/op
Iteration   1: 2.579 ±(99.9%) 0.005 ms/op
Iteration   2: 2.620 ±(99.9%) 0.004 ms/op
Iteration   3: 2.568 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.589 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (2.568, 2.589, 2.620), stdev = 0.027
  CI (99.9%): [2.094, 3.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
Iteration   3: 2.503 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.494 ±(99.9%) 0.453 ms/op [Average]
  (min, avg, max) = (2.465, 2.494, 2.512), stdev = 0.025
  CI (99.9%): [2.041, 2.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.173 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.558 ±(99.9%) 0.004 ms/op
Iteration   1: 2.565 ±(99.9%) 0.005 ms/op
Iteration   2: 2.577 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.567 ±(99.9%) 0.175 ms/op [Average]
  (min, avg, max) = (2.558, 2.567, 2.577), stdev = 0.010
  CI (99.9%): [2.392, 2.742] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.748 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.005 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
Iteration   2: 3.007 ±(99.9%) 0.007 ms/op
Iteration   3: 3.013 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.074 ms/op [Average]
  (min, avg, max) = (3.007, 3.011, 3.014), stdev = 0.004
  CI (99.9%): [2.937, 3.085] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.991 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.744 ms/op
                 createUser·p0.999:  11.223 ms/op
                 createUser·p0.9999: 13.865 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.504 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  9.158 ms/op
                 createUser·p0.9999: 12.803 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.307 ms/op
                 createUser·p0.9999: 10.961 ms/op
                 createUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381561
  mean =      2.513 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 185267 
    [ 2.500,  3.750) = 192610 
    [ 3.750,  5.000) = 2666 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     13.359 ms/op
     p(99.9990) =     14.584 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.789 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  7.174 ms/op
                 existUser·p0.9999: 13.729 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  6.322 ms/op
                 existUser·p0.9999: 13.220 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   3: 2.441 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  5.693 ms/op
                 existUser·p0.9999: 11.616 ms/op
                 existUser·p1.00:   12.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392536
  mean =      2.443 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 195678 
    [ 2.500,  3.750) = 193764 
    [ 3.750,  5.000) = 2291 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 111 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.147 ms/op
     p(99.9900) =     13.349 ms/op
     p(99.9990) =     13.831 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.006 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.109 ms/op
                 getUser·p0.99:   3.588 ms/op
                 getUser·p0.999:  6.357 ms/op
                 getUser·p0.9999: 13.850 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.957 ms/op
                 getUser·p0.95:   3.047 ms/op
                 getUser·p0.99:   3.428 ms/op
                 getUser·p0.999:  5.916 ms/op
                 getUser·p0.9999: 12.434 ms/op
                 getUser·p1.00:   12.911 ms/op

Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.813 ms/op
                 getUser·p0.999:  6.347 ms/op
                 getUser·p0.9999: 11.309 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389907
  mean =      2.460 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 195000 
    [ 2.500,  3.750) = 191818 
    [ 3.750,  5.000) = 2255 
    [ 5.000,  6.250) = 375 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.499 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.255 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.297 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.550 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.885 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.293 ms/op
                 listUser·p0.9999: 12.047 ms/op
                 listUser·p1.00:   12.911 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  8.807 ms/op
                 listUser·p0.9999: 10.597 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   3: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.480 ms/op
                 listUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319997
  mean =      2.997 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 129 
    [ 1.250,  2.500) = 96057 
    [ 2.500,  3.750) = 186202 
    [ 3.750,  5.000) = 30491 
    [ 5.000,  6.250) = 5750 
    [ 6.250,  7.500) = 729 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 256 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.854 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.159 ms/op
     p(99.9900) =     11.354 ms/op
     p(99.9990) =     12.776 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.564 ± 1.254  ops/ms
ClientPb.existUser                       thrpt       3  13.075 ± 1.784  ops/ms
ClientPb.getUser                         thrpt       3  12.506 ± 1.379  ops/ms
ClientPb.listUser                        thrpt       3  10.367 ± 2.173  ops/ms
ClientPb.createUser                       avgt       3   2.589 ± 0.495   ms/op
ClientPb.existUser                        avgt       3   2.494 ± 0.453   ms/op
ClientPb.getUser                          avgt       3   2.567 ± 0.175   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.074   ms/op
ClientPb.createUser                     sample  381561   2.513 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.816           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.405           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.359           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.942           ms/op
ClientPb.existUser                      sample  392536   2.443 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.570           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.147           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.349           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.877           ms/op
ClientPb.getUser                        sample  389907   2.460 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.772           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.499           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.986           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.255           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  319997   2.997 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.803           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.941           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.354           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
