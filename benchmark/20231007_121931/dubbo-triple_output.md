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
# Warmup Iteration   1: 1.054 ops/ms
# Warmup Iteration   2: 2.427 ops/ms
# Warmup Iteration   3: 5.045 ops/ms
Iteration   1: 5.730 ops/ms
Iteration   2: 6.176 ops/ms
Iteration   3: 6.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.055 ±(99.9%) 5.190 ops/ms [Average]
  (min, avg, max) = (5.730, 6.055, 6.259), stdev = 0.284
  CI (99.9%): [0.865, 11.245] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.704 ops/ms
# Warmup Iteration   2: 5.311 ops/ms
# Warmup Iteration   3: 6.115 ops/ms
Iteration   1: 6.212 ops/ms
Iteration   2: 6.245 ops/ms
Iteration   3: 6.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.195 ±(99.9%) 1.097 ops/ms [Average]
  (min, avg, max) = (6.128, 6.195, 6.245), stdev = 0.060
  CI (99.9%): [5.098, 7.292] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.588 ops/ms
# Warmup Iteration   2: 4.803 ops/ms
# Warmup Iteration   3: 6.000 ops/ms
Iteration   1: 6.054 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 6.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.976 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (5.787, 5.976, 6.088), stdev = 0.165
  CI (99.9%): [2.974, 8.979] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.674 ops/ms
# Warmup Iteration   2: 4.179 ops/ms
# Warmup Iteration   3: 5.127 ops/ms
Iteration   1: 5.248 ops/ms
Iteration   2: 5.033 ops/ms
Iteration   3: 5.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.129 ±(99.9%) 1.999 ops/ms [Average]
  (min, avg, max) = (5.033, 5.129, 5.248), stdev = 0.110
  CI (99.9%): [3.130, 7.127] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.936 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.084 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.429 ±(99.9%) 0.013 ms/op
Iteration   1: 5.348 ±(99.9%) 0.013 ms/op
Iteration   2: 5.320 ±(99.9%) 0.012 ms/op
Iteration   3: 5.298 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.322 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (5.298, 5.322, 5.348), stdev = 0.025
  CI (99.9%): [4.865, 5.778] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.012 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.877 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.067 ±(99.9%) 0.010 ms/op
Iteration   1: 5.165 ±(99.9%) 0.010 ms/op
Iteration   2: 5.110 ±(99.9%) 0.009 ms/op
Iteration   3: 5.087 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.120 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (5.087, 5.120, 5.165), stdev = 0.040
  CI (99.9%): [4.392, 5.849] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.318 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.410 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.442 ±(99.9%) 0.009 ms/op
Iteration   1: 5.431 ±(99.9%) 0.009 ms/op
Iteration   2: 5.290 ±(99.9%) 0.014 ms/op
Iteration   3: 5.158 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.293 ±(99.9%) 2.491 ms/op [Average]
  (min, avg, max) = (5.158, 5.293, 5.431), stdev = 0.137
  CI (99.9%): [2.802, 7.784] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.884 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 7.283 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 6.420 ±(99.9%) 0.011 ms/op
Iteration   1: 6.043 ±(99.9%) 0.020 ms/op
Iteration   2: 6.229 ±(99.9%) 0.011 ms/op
Iteration   3: 6.251 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.174 ±(99.9%) 2.089 ms/op [Average]
  (min, avg, max) = (6.043, 6.174, 6.251), stdev = 0.114
  CI (99.9%): [4.086, 8.263] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.302 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.932 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.682 ±(99.9%) 0.023 ms/op
Iteration   1: 5.376 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.343 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.595 ms/op
                 createUser·p0.95:   7.725 ms/op
                 createUser·p0.99:   9.886 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 38.407 ms/op
                 createUser·p1.00:   38.666 ms/op

Iteration   2: 5.446 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   5.226 ms/op
                 createUser·p0.90:   6.586 ms/op
                 createUser·p0.95:   7.242 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 28.169 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 5.340 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.466 ms/op
                 createUser·p0.50:   5.120 ms/op
                 createUser·p0.90:   6.324 ms/op
                 createUser·p0.95:   6.914 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  26.837 ms/op
                 createUser·p0.9999: 29.852 ms/op
                 createUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 178241
  mean =      5.387 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 74708 
    [ 5.000,  7.500) = 95982 
    [ 7.500, 10.000) = 5874 
    [10.000, 12.500) = 1038 
    [12.500, 15.000) = 252 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.496 ms/op
     p(95.0000) =      7.258 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     25.560 ms/op
     p(99.9900) =     35.335 ms/op
     p(99.9990) =     38.564 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 14.461 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.608 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.161 ±(99.9%) 0.018 ms/op
Iteration   1: 5.046 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.997 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   6.021 ms/op
                 existUser·p0.95:   6.799 ms/op
                 existUser·p0.99:   9.781 ms/op
                 existUser·p0.999:  22.815 ms/op
                 existUser·p0.9999: 26.945 ms/op
                 existUser·p1.00:   27.623 ms/op

Iteration   2: 5.007 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.647 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.930 ms/op
                 existUser·p0.99:   10.224 ms/op
                 existUser·p0.999:  24.974 ms/op
                 existUser·p0.9999: 28.254 ms/op
                 existUser·p1.00:   28.934 ms/op

Iteration   3: 5.171 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   4.948 ms/op
                 existUser·p0.90:   6.185 ms/op
                 existUser·p0.95:   6.914 ms/op
                 existUser·p0.99:   9.650 ms/op
                 existUser·p0.999:  26.386 ms/op
                 existUser·p0.9999: 31.093 ms/op
                 existUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188977
  mean =      5.074 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 112014 
    [ 5.000,  7.500) = 70339 
    [ 7.500, 10.000) = 4871 
    [10.000, 12.500) = 995 
    [12.500, 15.000) = 440 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.647 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.103 ms/op
     p(95.0000) =      6.889 ms/op
     p(99.0000) =      9.830 ms/op
     p(99.9000) =     23.135 ms/op
     p(99.9900) =     29.527 ms/op
     p(99.9990) =     32.035 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.169 ±(99.9%) 0.248 ms/op
# Warmup Iteration   2: 6.033 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.410 ±(99.9%) 0.019 ms/op
Iteration   1: 5.306 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.486 ms/op
                 getUser·p0.50:   5.095 ms/op
                 getUser·p0.90:   6.234 ms/op
                 getUser·p0.95:   7.078 ms/op
                 getUser·p0.99:   9.683 ms/op
                 getUser·p0.999:  24.394 ms/op
                 getUser·p0.9999: 29.031 ms/op
                 getUser·p1.00:   33.194 ms/op

Iteration   2: 5.395 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.603 ms/op
                 getUser·p0.95:   7.700 ms/op
                 getUser·p0.99:   10.420 ms/op
                 getUser·p0.999:  25.845 ms/op
                 getUser·p0.9999: 36.897 ms/op
                 getUser·p1.00:   38.732 ms/op

Iteration   3: 5.497 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.818 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.545 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   12.386 ms/op
                 getUser·p0.999:  27.781 ms/op
                 getUser·p0.9999: 31.773 ms/op
                 getUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 177792
  mean =      5.398 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 77247 
    [ 5.000,  7.500) = 91761 
    [ 7.500, 10.000) = 6376 
    [10.000, 12.500) = 1394 
    [12.500, 15.000) = 523 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      5.112 ms/op
     p(90.0000) =      6.455 ms/op
     p(95.0000) =      7.479 ms/op
     p(99.0000) =     10.797 ms/op
     p(99.9000) =     25.671 ms/op
     p(99.9900) =     34.865 ms/op
     p(99.9990) =     38.630 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


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
# Warmup Iteration   1: 18.155 ±(99.9%) 0.286 ms/op
# Warmup Iteration   2: 7.118 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.326 ±(99.9%) 0.024 ms/op
Iteration   1: 6.148 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.176 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  28.800 ms/op
                 listUser·p0.9999: 34.506 ms/op
                 listUser·p1.00:   34.996 ms/op

Iteration   2: 6.213 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.036 ms/op
                 listUser·p0.99:   11.338 ms/op
                 listUser·p0.999:  29.605 ms/op
                 listUser·p0.9999: 37.683 ms/op
                 listUser·p1.00:   39.453 ms/op

Iteration   3: 6.275 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.843 ms/op
                 listUser·p0.50:   5.923 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.518 ms/op
                 listUser·p0.999:  21.398 ms/op
                 listUser·p0.9999: 25.065 ms/op
                 listUser·p1.00:   28.279 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 154602
  mean =      6.212 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 8593 
    [ 5.000,  7.500) = 133000 
    [ 7.500, 10.000) = 9623 
    [10.000, 12.500) = 2361 
    [12.500, 15.000) = 450 
    [15.000, 17.500) = 169 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      2.486 ms/op
     p(50.0000) =      5.915 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     27.066 ms/op
     p(99.9900) =     36.282 ms/op
     p(99.9990) =     39.023 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.055 ± 5.190  ops/ms
ClientPb.existUser                       thrpt       3   6.195 ± 1.097  ops/ms
ClientPb.getUser                         thrpt       3   5.976 ± 3.003  ops/ms
ClientPb.listUser                        thrpt       3   5.129 ± 1.999  ops/ms
ClientPb.createUser                       avgt       3   5.322 ± 0.457   ms/op
ClientPb.existUser                        avgt       3   5.120 ± 0.728   ms/op
ClientPb.getUser                          avgt       3   5.293 ± 2.491   ms/op
ClientPb.listUser                         avgt       3   6.174 ± 2.089   ms/op
ClientPb.createUser                     sample  178241   5.387 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.204           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.496           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.258           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.896           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.560           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.335           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.666           ms/op
ClientPb.existUser                      sample  188977   5.074 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.647           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.833           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.889           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.830           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.135           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.527           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.997           ms/op
ClientPb.getUser                        sample  177792   5.398 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.486           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.479           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.797           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.671           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.865           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.732           ms/op
ClientPb.listUser                       sample  154602   6.212 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.486           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.915           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.307           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.298           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.321           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.066           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.282           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.453           ms/op
