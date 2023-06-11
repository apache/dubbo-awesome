# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.567 ops/ms
# Warmup Iteration   2: 6.789 ops/ms
# Warmup Iteration   3: 9.358 ops/ms
Iteration   1: 10.132 ops/ms
Iteration   2: 9.932 ops/ms
Iteration   3: 9.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.944 ±(99.9%) 3.317 ops/ms [Average]
  (min, avg, max) = (9.769, 9.944, 10.132), stdev = 0.182
  CI (99.9%): [6.627, 13.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.424 ops/ms
# Warmup Iteration   2: 9.465 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.221 ops/ms
Iteration   2: 10.241 ops/ms
Iteration   3: 10.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.253 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (10.221, 10.253, 10.298), stdev = 0.040
  CI (99.9%): [9.524, 10.982] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.213 ops/ms
# Warmup Iteration   2: 8.683 ops/ms
# Warmup Iteration   3: 9.785 ops/ms
Iteration   1: 10.042 ops/ms
Iteration   2: 9.979 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.108 ±(99.9%) 3.143 ops/ms [Average]
  (min, avg, max) = (9.979, 10.108, 10.304), stdev = 0.172
  CI (99.9%): [6.965, 13.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.171 ops/ms
# Warmup Iteration   2: 7.884 ops/ms
# Warmup Iteration   3: 8.225 ops/ms
Iteration   1: 8.476 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.448 ±(99.9%) 1.714 ops/ms [Average]
  (min, avg, max) = (8.344, 8.448, 8.525), stdev = 0.094
  CI (99.9%): [6.735, 10.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.828 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.003 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.006 ms/op
Iteration   3: 3.107 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.152 ±(99.9%) 0.778 ms/op [Average]
  (min, avg, max) = (3.107, 3.152, 3.192), stdev = 0.043
  CI (99.9%): [2.375, 3.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.161 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.004 ms/op
Iteration   1: 3.110 ±(99.9%) 0.008 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.189 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.126 ±(99.9%) 1.045 ms/op [Average]
  (min, avg, max) = (3.077, 3.126, 3.189), stdev = 0.057
  CI (99.9%): [2.081, 4.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.465 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.005 ms/op
Iteration   1: 3.199 ±(99.9%) 0.003 ms/op
Iteration   2: 3.217 ±(99.9%) 0.004 ms/op
Iteration   3: 3.302 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.239 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.199, 3.239, 3.302), stdev = 0.055
  CI (99.9%): [2.237, 4.242] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.007 ms/op
Iteration   1: 3.792 ±(99.9%) 0.008 ms/op
Iteration   2: 3.769 ±(99.9%) 0.009 ms/op
Iteration   3: 3.772 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.778 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (3.769, 3.778, 3.792), stdev = 0.012
  CI (99.9%): [3.552, 4.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.898 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.010 ms/op
Iteration   1: 3.320 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.155 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 25.977 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.701 ms/op
                 createUser·p0.999:  13.667 ms/op
                 createUser·p0.9999: 22.987 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 3.212 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  14.830 ms/op
                 createUser·p0.9999: 19.863 ms/op
                 createUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297366
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16950 
    [ 2.500,  5.000) = 273935 
    [ 5.000,  7.500) = 5539 
    [ 7.500, 10.000) = 475 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     15.139 ms/op
     p(99.9900) =     24.790 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.207 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
Iteration   1: 3.289 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  11.007 ms/op
                 existUser·p0.9999: 19.867 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.139 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   27.132 ms/op

Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.329 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  12.091 ms/op
                 existUser·p0.9999: 22.372 ms/op
                 existUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301603
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23846 
    [ 2.500,  5.000) = 272743 
    [ 5.000,  7.500) = 4125 
    [ 7.500, 10.000) = 400 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     11.465 ms/op
     p(99.9900) =     24.800 ms/op
     p(99.9990) =     26.436 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.506 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.010 ms/op
Iteration   1: 3.328 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  17.571 ms/op
                 getUser·p0.9999: 26.732 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.571 ms/op
                 getUser·p0.999:  13.380 ms/op
                 getUser·p0.9999: 24.486 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.339 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  15.118 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293649
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14671 
    [ 2.500,  5.000) = 271325 
    [ 5.000,  7.500) = 6735 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     14.298 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     27.101 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.138 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
Iteration   1: 3.826 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.920 ms/op
                 listUser·p0.9999: 22.467 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   2: 3.789 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.306 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.018 ms/op
                 listUser·p0.9999: 16.318 ms/op
                 listUser·p1.00:   16.351 ms/op

Iteration   3: 3.822 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  12.358 ms/op
                 listUser·p0.9999: 13.628 ms/op
                 listUser·p1.00:   13.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251813
  mean =      3.812 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 243623 
    [ 5.000,  7.500) = 6246 
    [ 7.500, 10.000) = 1159 
    [10.000, 12.500) = 363 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      7.011 ms/op
     p(99.9000) =     13.602 ms/op
     p(99.9900) =     21.347 ms/op
     p(99.9990) =     23.084 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.944 ± 3.317  ops/ms
ClientPb.existUser                       thrpt       3  10.253 ± 0.729  ops/ms
ClientPb.getUser                         thrpt       3  10.108 ± 3.143  ops/ms
ClientPb.listUser                        thrpt       3   8.448 ± 1.714  ops/ms
ClientPb.createUser                       avgt       3   3.152 ± 0.778   ms/op
ClientPb.existUser                        avgt       3   3.126 ± 1.045   ms/op
ClientPb.getUser                          avgt       3   3.239 ± 1.002   ms/op
ClientPb.listUser                         avgt       3   3.778 ± 0.226   ms/op
ClientPb.createUser                     sample  297366   3.229 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.155           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.139           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.790           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.427           ms/op
ClientPb.existUser                      sample  301603   3.181 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.506           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.441           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.341           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.465           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.800           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.132           ms/op
ClientPb.getUser                        sample  293649   3.267 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.886           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.298           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.100           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.918           ms/op
ClientPb.listUser                       sample  251813   3.812 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.602           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.347           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.101           ms/op
