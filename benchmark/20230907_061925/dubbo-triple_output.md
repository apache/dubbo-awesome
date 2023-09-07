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
# Warmup Iteration   1: 1.384 ops/ms
# Warmup Iteration   2: 2.715 ops/ms
# Warmup Iteration   3: 5.229 ops/ms
Iteration   1: 5.885 ops/ms
Iteration   2: 6.664 ops/ms
Iteration   3: 6.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.508 ±(99.9%) 10.255 ops/ms [Average]
  (min, avg, max) = (5.885, 6.508, 6.976), stdev = 0.562
  CI (99.9%): [≈ 0, 16.763] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.886 ops/ms
# Warmup Iteration   2: 5.220 ops/ms
# Warmup Iteration   3: 6.815 ops/ms
Iteration   1: 6.850 ops/ms
Iteration   2: 6.770 ops/ms
Iteration   3: 7.450 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.023 ±(99.9%) 6.786 ops/ms [Average]
  (min, avg, max) = (6.770, 7.023, 7.450), stdev = 0.372
  CI (99.9%): [0.237, 13.810] (assumes normal distribution)


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
# Warmup Iteration   1: 2.104 ops/ms
# Warmup Iteration   2: 5.120 ops/ms
# Warmup Iteration   3: 6.054 ops/ms
Iteration   1: 6.571 ops/ms
Iteration   2: 7.417 ops/ms
Iteration   3: 6.966 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.985 ±(99.9%) 7.723 ops/ms [Average]
  (min, avg, max) = (6.571, 6.985, 7.417), stdev = 0.423
  CI (99.9%): [≈ 0, 14.708] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.907 ops/ms
# Warmup Iteration   2: 4.562 ops/ms
# Warmup Iteration   3: 5.096 ops/ms
Iteration   1: 6.104 ops/ms
Iteration   2: 5.689 ops/ms
Iteration   3: 5.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.745 ±(99.9%) 6.103 ops/ms [Average]
  (min, avg, max) = (5.442, 5.745, 6.104), stdev = 0.335
  CI (99.9%): [≈ 0, 11.848] (assumes normal distribution)


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
# Warmup Iteration   1: 15.112 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.699 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.038 ±(99.9%) 0.010 ms/op
Iteration   1: 4.980 ±(99.9%) 0.009 ms/op
Iteration   2: 4.934 ±(99.9%) 0.007 ms/op
Iteration   3: 4.744 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.886 ±(99.9%) 2.287 ms/op [Average]
  (min, avg, max) = (4.744, 4.886, 4.980), stdev = 0.125
  CI (99.9%): [2.599, 7.173] (assumes normal distribution)


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
# Warmup Iteration   1: 12.947 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.838 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.006 ms/op
Iteration   1: 4.313 ±(99.9%) 0.007 ms/op
Iteration   2: 4.256 ±(99.9%) 0.007 ms/op
Iteration   3: 4.269 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.279 ±(99.9%) 0.551 ms/op [Average]
  (min, avg, max) = (4.256, 4.279, 4.313), stdev = 0.030
  CI (99.9%): [3.728, 4.830] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 15.517 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.967 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.003 ms/op
Iteration   1: 4.524 ±(99.9%) 0.006 ms/op
Iteration   2: 4.174 ±(99.9%) 0.007 ms/op
Iteration   3: 4.396 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.364 ±(99.9%) 3.235 ms/op [Average]
  (min, avg, max) = (4.174, 4.364, 4.524), stdev = 0.177
  CI (99.9%): [1.129, 7.600] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 17.439 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.996 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.673 ±(99.9%) 0.008 ms/op
Iteration   1: 5.695 ±(99.9%) 0.008 ms/op
Iteration   2: 5.269 ±(99.9%) 0.010 ms/op
Iteration   3: 4.996 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.320 ±(99.9%) 6.432 ms/op [Average]
  (min, avg, max) = (4.996, 5.320, 5.695), stdev = 0.353
  CI (99.9%): [≈ 0, 11.752] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.779 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.923 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.945 ±(99.9%) 0.024 ms/op
Iteration   1: 4.413 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   5.685 ms/op
                 createUser·p0.95:   6.644 ms/op
                 createUser·p0.99:   9.798 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 31.547 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   2: 4.348 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.019 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.423 ms/op
                 createUser·p0.95:   6.644 ms/op
                 createUser·p0.99:   9.535 ms/op
                 createUser·p0.999:  28.261 ms/op
                 createUser·p0.9999: 31.773 ms/op
                 createUser·p1.00:   32.637 ms/op

Iteration   3: 4.202 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.903 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.603 ms/op
                 createUser·p0.99:   8.503 ms/op
                 createUser·p0.999:  16.235 ms/op
                 createUser·p0.9999: 40.265 ms/op
                 createUser·p1.00:   42.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 222151
  mean =      4.319 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 192032 
    [ 5.000, 10.000) = 28549 
    [10.000, 15.000) = 1271 
    [15.000, 20.000) = 58 
    [20.000, 25.000) = 17 
    [25.000, 30.000) = 99 
    [30.000, 35.000) = 92 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     26.968 ms/op
     p(99.9900) =     39.059 ms/op
     p(99.9990) =     42.031 ms/op
     p(99.9999) =     42.271 ms/op
    p(100.0000) =     42.271 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.828 ±(99.9%) 0.250 ms/op
# Warmup Iteration   2: 4.823 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.024 ms/op
Iteration   1: 5.004 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   4.350 ms/op
                 existUser·p0.90:   7.111 ms/op
                 existUser·p0.95:   8.471 ms/op
                 existUser·p0.99:   12.288 ms/op
                 existUser·p0.999:  17.538 ms/op
                 existUser·p0.9999: 24.924 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 5.081 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.399 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   6.865 ms/op
                 existUser·p0.95:   8.004 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  27.189 ms/op
                 existUser·p0.9999: 35.566 ms/op
                 existUser·p1.00:   36.700 ms/op

Iteration   3: 4.551 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.544 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   6.226 ms/op
                 existUser·p0.95:   7.242 ms/op
                 existUser·p0.99:   10.289 ms/op
                 existUser·p0.999:  18.203 ms/op
                 existUser·p0.9999: 31.747 ms/op
                 existUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 197188
  mean =      4.867 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 219 
    [ 2.500,  5.000) = 133857 
    [ 5.000,  7.500) = 50753 
    [ 7.500, 10.000) = 8984 
    [10.000, 12.500) = 2218 
    [12.500, 15.000) = 687 
    [15.000, 17.500) = 271 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 54 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      6.758 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     11.207 ms/op
     p(99.9000) =     17.623 ms/op
     p(99.9900) =     32.735 ms/op
     p(99.9990) =     35.872 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 16.322 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 6.478 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.174 ±(99.9%) 0.023 ms/op
Iteration   1: 4.274 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.322 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   6.349 ms/op
                 getUser·p0.99:   10.256 ms/op
                 getUser·p0.999:  16.253 ms/op
                 getUser·p0.9999: 42.009 ms/op
                 getUser·p1.00:   44.171 ms/op

Iteration   2: 4.235 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.095 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.833 ms/op
                 getUser·p0.95:   6.169 ms/op
                 getUser·p0.99:   9.290 ms/op
                 getUser·p0.999:  26.230 ms/op
                 getUser·p0.9999: 28.891 ms/op
                 getUser·p1.00:   29.491 ms/op

Iteration   3: 4.397 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.399 ms/op
                 getUser·p0.95:   6.283 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  13.818 ms/op
                 getUser·p0.9999: 33.817 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 223147
  mean =      4.301 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 199082 
    [ 5.000, 10.000) = 22298 
    [10.000, 15.000) = 1465 
    [15.000, 20.000) = 78 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 152 
    [30.000, 35.000) = 37 
    [35.000, 40.000) = 10 
    [40.000, 45.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      6.275 ms/op
     p(99.0000) =      9.322 ms/op
     p(99.9000) =     25.030 ms/op
     p(99.9900) =     40.546 ms/op
     p(99.9990) =     42.074 ms/op
     p(99.9999) =     44.171 ms/op
    p(100.0000) =     44.171 ms/op


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
# Warmup Iteration   1: 16.243 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 7.009 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.224 ±(99.9%) 0.032 ms/op
Iteration   1: 5.950 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.864 ms/op
                 listUser·p0.95:   9.126 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  48.431 ms/op
                 listUser·p0.9999: 58.401 ms/op
                 listUser·p1.00:   59.441 ms/op

Iteration   2: 5.334 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.673 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.980 ms/op
                 listUser·p0.95:   8.421 ms/op
                 listUser·p0.99:   12.206 ms/op
                 listUser·p0.999:  27.984 ms/op
                 listUser·p0.9999: 35.522 ms/op
                 listUser·p1.00:   36.635 ms/op

Iteration   3: 5.674 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.054 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   8.604 ms/op
                 listUser·p0.99:   11.813 ms/op
                 listUser·p0.999:  19.946 ms/op
                 listUser·p0.9999: 25.899 ms/op
                 listUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 169948
  mean =      5.641 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78692 
    [ 5.000, 10.000) = 86922 
    [10.000, 15.000) = 3658 
    [15.000, 20.000) = 332 
    [20.000, 25.000) = 106 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 33 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 28 
    [50.000, 55.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.673 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      7.545 ms/op
     p(95.0000) =      8.684 ms/op
     p(99.0000) =     12.321 ms/op
     p(99.9000) =     27.068 ms/op
     p(99.9900) =     53.938 ms/op
     p(99.9990) =     59.349 ms/op
     p(99.9999) =     59.441 ms/op
    p(100.0000) =     59.441 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   6.508 ± 10.255  ops/ms
ClientPb.existUser                       thrpt       3   7.023 ±  6.786  ops/ms
ClientPb.getUser                         thrpt       3   6.985 ±  7.723  ops/ms
ClientPb.listUser                        thrpt       3   5.745 ±  6.103  ops/ms
ClientPb.createUser                       avgt       3   4.886 ±  2.287   ms/op
ClientPb.existUser                        avgt       3   4.279 ±  0.551   ms/op
ClientPb.getUser                          avgt       3   4.364 ±  3.235   ms/op
ClientPb.listUser                         avgt       3   5.320 ±  6.432   ms/op
ClientPb.createUser                     sample  222151   4.319 ±  0.010   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.087            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.994            ms/op
ClientPb.createUser:createUser·p0.90    sample           5.325            ms/op
ClientPb.createUser:createUser·p0.95    sample           6.439            ms/op
ClientPb.createUser:createUser·p0.99    sample           9.322            ms/op
ClientPb.createUser:createUser·p0.999   sample          26.968            ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.059            ms/op
ClientPb.createUser:createUser·p1.00    sample          42.271            ms/op
ClientPb.existUser                      sample  197188   4.867 ±  0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.399            ms/op
ClientPb.existUser:existUser·p0.50      sample           4.293            ms/op
ClientPb.existUser:existUser·p0.90      sample           6.758            ms/op
ClientPb.existUser:existUser·p0.95      sample           7.889            ms/op
ClientPb.existUser:existUser·p0.99      sample          11.207            ms/op
ClientPb.existUser:existUser·p0.999     sample          17.623            ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.735            ms/op
ClientPb.existUser:existUser·p1.00      sample          36.700            ms/op
ClientPb.getUser                        sample  223147   4.301 ±  0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.704            ms/op
ClientPb.getUser:getUser·p0.50          sample           4.002            ms/op
ClientPb.getUser:getUser·p0.90          sample           5.079            ms/op
ClientPb.getUser:getUser·p0.95          sample           6.275            ms/op
ClientPb.getUser:getUser·p0.99          sample           9.322            ms/op
ClientPb.getUser:getUser·p0.999         sample          25.030            ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.546            ms/op
ClientPb.getUser:getUser·p1.00          sample          44.171            ms/op
ClientPb.listUser                       sample  169948   5.641 ±  0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.673            ms/op
ClientPb.listUser:listUser·p0.50        sample           5.079            ms/op
ClientPb.listUser:listUser·p0.90        sample           7.545            ms/op
ClientPb.listUser:listUser·p0.95        sample           8.684            ms/op
ClientPb.listUser:listUser·p0.99        sample          12.321            ms/op
ClientPb.listUser:listUser·p0.999       sample          27.068            ms/op
ClientPb.listUser:listUser·p0.9999      sample          53.938            ms/op
ClientPb.listUser:listUser·p1.00        sample          59.441            ms/op
