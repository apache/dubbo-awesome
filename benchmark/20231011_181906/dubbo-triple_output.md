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
# Warmup Iteration   1: 1.252 ops/ms
# Warmup Iteration   2: 2.448 ops/ms
# Warmup Iteration   3: 5.685 ops/ms
Iteration   1: 5.933 ops/ms
Iteration   2: 6.060 ops/ms
Iteration   3: 5.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.985 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (5.933, 5.985, 6.060), stdev = 0.067
  CI (99.9%): [4.769, 7.200] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 5.245 ops/ms
# Warmup Iteration   3: 6.363 ops/ms
Iteration   1: 6.466 ops/ms
Iteration   2: 6.241 ops/ms
Iteration   3: 6.397 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.368 ±(99.9%) 2.102 ops/ms [Average]
  (min, avg, max) = (6.241, 6.368, 6.466), stdev = 0.115
  CI (99.9%): [4.266, 8.470] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.602 ops/ms
# Warmup Iteration   2: 5.241 ops/ms
# Warmup Iteration   3: 5.954 ops/ms
Iteration   1: 5.979 ops/ms
Iteration   2: 5.950 ops/ms
Iteration   3: 6.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.081 ±(99.9%) 3.712 ops/ms [Average]
  (min, avg, max) = (5.950, 6.081, 6.316), stdev = 0.203
  CI (99.9%): [2.369, 9.793] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.423 ops/ms
# Warmup Iteration   2: 3.820 ops/ms
# Warmup Iteration   3: 5.134 ops/ms
Iteration   1: 4.736 ops/ms
Iteration   2: 4.928 ops/ms
Iteration   3: 5.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.965 ±(99.9%) 4.544 ops/ms [Average]
  (min, avg, max) = (4.736, 4.965, 5.230), stdev = 0.249
  CI (99.9%): [0.421, 9.509] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 17.007 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.622 ±(99.9%) 0.007 ms/op
Iteration   1: 5.258 ±(99.9%) 0.009 ms/op
Iteration   2: 5.224 ±(99.9%) 0.009 ms/op
Iteration   3: 5.269 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.251 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (5.224, 5.251, 5.269), stdev = 0.024
  CI (99.9%): [4.819, 5.682] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.471 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.770 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.166 ±(99.9%) 0.006 ms/op
Iteration   1: 4.911 ±(99.9%) 0.009 ms/op
Iteration   2: 4.877 ±(99.9%) 0.014 ms/op
Iteration   3: 4.918 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.902 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (4.877, 4.902, 4.918), stdev = 0.022
  CI (99.9%): [4.502, 5.302] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 15.674 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 6.198 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.393 ±(99.9%) 0.007 ms/op
Iteration   1: 5.336 ±(99.9%) 0.006 ms/op
Iteration   2: 5.355 ±(99.9%) 0.006 ms/op
Iteration   3: 5.321 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.337 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (5.321, 5.337, 5.355), stdev = 0.017
  CI (99.9%): [5.024, 5.651] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 19.527 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.989 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.252 ±(99.9%) 0.007 ms/op
Iteration   1: 6.224 ±(99.9%) 0.013 ms/op
Iteration   2: 6.270 ±(99.9%) 0.007 ms/op
Iteration   3: 5.890 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.128 ±(99.9%) 3.787 ms/op [Average]
  (min, avg, max) = (5.890, 6.128, 6.270), stdev = 0.208
  CI (99.9%): [2.340, 9.915] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.656 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 6.420 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.605 ±(99.9%) 0.025 ms/op
Iteration   1: 5.205 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.183 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   6.873 ms/op
                 createUser·p0.99:   9.138 ms/op
                 createUser·p0.999:  21.360 ms/op
                 createUser·p0.9999: 30.306 ms/op
                 createUser·p1.00:   33.620 ms/op

Iteration   2: 5.322 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.778 ms/op
                 createUser·p0.50:   5.104 ms/op
                 createUser·p0.90:   6.373 ms/op
                 createUser·p0.95:   6.988 ms/op
                 createUser·p0.99:   9.765 ms/op
                 createUser·p0.999:  27.917 ms/op
                 createUser·p0.9999: 31.785 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   3: 5.339 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   1.513 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.455 ms/op
                 createUser·p0.95:   7.225 ms/op
                 createUser·p0.99:   10.568 ms/op
                 createUser·p0.999:  30.086 ms/op
                 createUser·p0.9999: 34.538 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181434
  mean =      5.288 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 84522 
    [ 5.000,  7.500) = 90476 
    [ 7.500, 10.000) = 4676 
    [10.000, 12.500) = 1134 
    [12.500, 15.000) = 362 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 85 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.012 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     21.982 ms/op
     p(99.9900) =     33.447 ms/op
     p(99.9990) =     34.955 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 15.357 ±(99.9%) 0.258 ms/op
# Warmup Iteration   2: 5.783 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.298 ±(99.9%) 0.021 ms/op
Iteration   1: 5.370 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.376 ms/op
                 existUser·p0.50:   4.973 ms/op
                 existUser·p0.90:   6.996 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   10.994 ms/op
                 existUser·p0.999:  27.453 ms/op
                 existUser·p0.9999: 33.360 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   2: 5.280 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.995 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.291 ms/op
                 existUser·p0.95:   7.234 ms/op
                 existUser·p0.99:   10.863 ms/op
                 existUser·p0.999:  26.491 ms/op
                 existUser·p0.9999: 30.338 ms/op
                 existUser·p1.00:   30.704 ms/op

Iteration   3: 5.298 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.359 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.135 ms/op
                 existUser·p0.99:   10.011 ms/op
                 existUser·p0.999:  29.098 ms/op
                 existUser·p0.9999: 33.029 ms/op
                 existUser·p1.00:   33.128 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 180491
  mean =      5.316 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 88878 
    [ 5.000,  7.500) = 81933 
    [ 7.500, 10.000) = 7157 
    [10.000, 12.500) = 1647 
    [12.500, 15.000) = 508 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.995 ms/op
     p(50.0000) =      5.014 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.651 ms/op
     p(99.0000) =     10.733 ms/op
     p(99.9000) =     27.181 ms/op
     p(99.9900) =     33.030 ms/op
     p(99.9990) =     34.052 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.044 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 6.828 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.822 ±(99.9%) 0.024 ms/op
Iteration   1: 5.579 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.980 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   12.255 ms/op
                 getUser·p0.999:  24.696 ms/op
                 getUser·p0.9999: 27.280 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 5.772 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.675 ms/op
                 getUser·p0.50:   5.431 ms/op
                 getUser·p0.90:   7.243 ms/op
                 getUser·p0.95:   8.831 ms/op
                 getUser·p0.99:   12.042 ms/op
                 getUser·p0.999:  18.769 ms/op
                 getUser·p0.9999: 28.203 ms/op
                 getUser·p1.00:   30.179 ms/op

Iteration   3: 5.282 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.860 ms/op
                 getUser·p0.50:   4.973 ms/op
                 getUser·p0.90:   6.500 ms/op
                 getUser·p0.95:   7.873 ms/op
                 getUser·p0.99:   10.699 ms/op
                 getUser·p0.999:  26.504 ms/op
                 getUser·p0.9999: 30.594 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 173318
  mean =      5.537 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 67088 
    [ 5.000,  7.500) = 94333 
    [ 7.500, 10.000) = 7896 
    [10.000, 12.500) = 2787 
    [12.500, 15.000) = 684 
    [15.000, 17.500) = 247 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.791 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     11.747 ms/op
     p(99.9000) =     22.173 ms/op
     p(99.9900) =     28.727 ms/op
     p(99.9990) =     31.016 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.134 ±(99.9%) 0.377 ms/op
# Warmup Iteration   2: 7.075 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.477 ±(99.9%) 0.027 ms/op
Iteration   1: 6.231 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   9.322 ms/op
                 listUser·p0.99:   12.878 ms/op
                 listUser·p0.999:  28.529 ms/op
                 listUser·p0.9999: 31.088 ms/op
                 listUser·p1.00:   31.752 ms/op

Iteration   2: 5.973 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.774 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   7.045 ms/op
                 listUser·p0.95:   8.053 ms/op
                 listUser·p0.99:   11.485 ms/op
                 listUser·p0.999:  26.423 ms/op
                 listUser·p0.9999: 30.126 ms/op
                 listUser·p1.00:   31.457 ms/op

Iteration   3: 6.281 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.083 ms/op
                 listUser·p0.50:   6.005 ms/op
                 listUser·p0.90:   7.414 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  27.593 ms/op
                 listUser·p0.9999: 38.922 ms/op
                 listUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 155965
  mean =      6.158 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 14657 
    [ 5.000,  7.500) = 127351 
    [ 7.500, 10.000) = 9702 
    [10.000, 12.500) = 2778 
    [12.500, 15.000) = 953 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 95 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.774 ms/op
     p(50.0000) =      5.825 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     12.337 ms/op
     p(99.9000) =     27.625 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


# Run complete. Total time: 00:13:21

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.985 ± 1.215  ops/ms
ClientPb.existUser                       thrpt       3   6.368 ± 2.102  ops/ms
ClientPb.getUser                         thrpt       3   6.081 ± 3.712  ops/ms
ClientPb.listUser                        thrpt       3   4.965 ± 4.544  ops/ms
ClientPb.createUser                       avgt       3   5.251 ± 0.432   ms/op
ClientPb.existUser                        avgt       3   4.902 ± 0.400   ms/op
ClientPb.getUser                          avgt       3   5.337 ± 0.314   ms/op
ClientPb.listUser                         avgt       3   6.128 ± 3.787   ms/op
ClientPb.createUser                     sample  181434   5.288 ± 0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.513           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.373           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.012           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.982           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.447           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  180491   5.316 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.995           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.521           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.651           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.733           ms/op
ClientPb.existUser:existUser·p0.999     sample          27.181           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.030           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  173318   5.537 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.860           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.791           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.258           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.747           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.173           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.727           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.064           ms/op
ClientPb.listUser                       sample  155965   6.158 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.774           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.618           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.337           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.625           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.142           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.059           ms/op
