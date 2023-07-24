# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.706 ops/ms
# Warmup Iteration   2: 6.705 ops/ms
# Warmup Iteration   3: 9.139 ops/ms
Iteration   1: 9.810 ops/ms
Iteration   2: 9.832 ops/ms
Iteration   3: 9.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.813 ±(99.9%) 0.327 ops/ms [Average]
  (min, avg, max) = (9.796, 9.813, 9.832), stdev = 0.018
  CI (99.9%): [9.485, 10.140] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 9.784 ops/ms
# Warmup Iteration   3: 9.921 ops/ms
Iteration   1: 10.619 ops/ms
Iteration   2: 10.203 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.406 ±(99.9%) 3.800 ops/ms [Average]
  (min, avg, max) = (10.203, 10.406, 10.619), stdev = 0.208
  CI (99.9%): [6.606, 14.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ops/ms
# Warmup Iteration   2: 8.997 ops/ms
# Warmup Iteration   3: 9.248 ops/ms
Iteration   1: 9.607 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 10.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.861 ±(99.9%) 4.031 ops/ms [Average]
  (min, avg, max) = (9.607, 9.861, 10.008), stdev = 0.221
  CI (99.9%): [5.830, 13.892] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 8.173 ops/ms
Iteration   1: 8.570 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.529 ±(99.9%) 0.684 ops/ms [Average]
  (min, avg, max) = (8.496, 8.529, 8.570), stdev = 0.037
  CI (99.9%): [7.845, 9.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.005 ms/op
Iteration   1: 3.144 ±(99.9%) 0.006 ms/op
Iteration   2: 3.163 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.130 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.084, 3.130, 3.163), stdev = 0.041
  CI (99.9%): [2.377, 3.884] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.814 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.002 ms/op
Iteration   1: 3.069 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.138 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.078 ±(99.9%) 1.018 ms/op [Average]
  (min, avg, max) = (3.027, 3.078, 3.138), stdev = 0.056
  CI (99.9%): [2.060, 4.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.319 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.004 ms/op
Iteration   1: 3.143 ±(99.9%) 0.002 ms/op
Iteration   2: 3.201 ±(99.9%) 0.006 ms/op
Iteration   3: 3.165 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.170 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.143, 3.170, 3.201), stdev = 0.029
  CI (99.9%): [2.635, 3.705] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.029 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.878 ±(99.9%) 0.005 ms/op
Iteration   1: 3.810 ±(99.9%) 0.009 ms/op
Iteration   2: 3.753 ±(99.9%) 0.011 ms/op
Iteration   3: 3.862 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.808 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (3.753, 3.808, 3.862), stdev = 0.055
  CI (99.9%): [2.809, 4.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.088 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
Iteration   1: 3.225 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.280 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  13.827 ms/op
                 createUser·p0.9999: 20.810 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 3.396 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  18.718 ms/op
                 createUser·p0.9999: 27.675 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   3: 3.285 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.955 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  12.534 ms/op
                 createUser·p0.9999: 22.323 ms/op
                 createUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 290898
  mean =      3.301 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13666 
    [ 2.500,  5.000) = 271124 
    [ 5.000,  7.500) = 5301 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.280 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     14.387 ms/op
     p(99.9900) =     26.932 ms/op
     p(99.9990) =     28.076 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.744 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.008 ms/op
Iteration   1: 3.084 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.300 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.703 ms/op
                 existUser·p0.999:  14.369 ms/op
                 existUser·p0.9999: 22.466 ms/op
                 existUser·p1.00:   23.462 ms/op

Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.460 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  11.030 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.229 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   5.293 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 23.010 ms/op
                 existUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313181
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17745 
    [ 2.500,  5.000) = 291907 
    [ 5.000,  7.500) = 2829 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.229 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      5.210 ms/op
     p(99.9000) =     14.068 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.768 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.048 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.542 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.010 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  12.265 ms/op
                 getUser·p0.9999: 20.179 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.245 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.450 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  17.054 ms/op
                 getUser·p0.9999: 23.926 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.114 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.792 ms/op
                 getUser·p0.999:  12.764 ms/op
                 getUser·p0.9999: 27.167 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296702
  mean =      3.233 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10235 
    [ 2.500,  5.000) = 278283 
    [ 5.000,  7.500) = 7170 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     24.368 ms/op
     p(99.9990) =     27.564 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.458 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.013 ms/op
Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 22.816 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.780 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  19.149 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   3: 3.777 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  12.293 ms/op
                 listUser·p0.9999: 14.057 ms/op
                 listUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256428
  mean =      3.743 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 78 
    [ 2.500,  5.000) = 248150 
    [ 5.000,  7.500) = 5937 
    [ 7.500, 10.000) = 1546 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     14.762 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.342 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.813 ± 0.327  ops/ms
ClientPb.existUser                       thrpt       3  10.406 ± 3.800  ops/ms
ClientPb.getUser                         thrpt       3   9.861 ± 4.031  ops/ms
ClientPb.listUser                        thrpt       3   8.529 ± 0.684  ops/ms
ClientPb.createUser                       avgt       3   3.130 ± 0.753   ms/op
ClientPb.existUser                        avgt       3   3.078 ± 1.018   ms/op
ClientPb.getUser                          avgt       3   3.170 ± 0.535   ms/op
ClientPb.listUser                         avgt       3   3.808 ± 0.999   ms/op
ClientPb.createUser                     sample  290898   3.301 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.280           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.387           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.932           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.310           ms/op
ClientPb.existUser                      sample  313181   3.064 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.229           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.210           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.068           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  296702   3.233 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.114           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.303           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.368           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.984           ms/op
ClientPb.listUser                       sample  256428   3.743 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.212           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.276           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.762           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.658           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.002           ms/op
