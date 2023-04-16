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
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 6.657 ops/ms
# Warmup Iteration   3: 9.025 ops/ms
Iteration   1: 9.967 ops/ms
Iteration   2: 9.821 ops/ms
Iteration   3: 9.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.787 ±(99.9%) 3.620 ops/ms [Average]
  (min, avg, max) = (9.574, 9.787, 9.967), stdev = 0.198
  CI (99.9%): [6.167, 13.407] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
# Warmup Iteration   2: 9.845 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 10.422 ops/ms
Iteration   2: 10.626 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.577 ±(99.9%) 2.492 ops/ms [Average]
  (min, avg, max) = (10.422, 10.577, 10.682), stdev = 0.137
  CI (99.9%): [8.085, 13.069] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.631 ops/ms
# Warmup Iteration   2: 9.031 ops/ms
# Warmup Iteration   3: 9.873 ops/ms
Iteration   1: 9.665 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 9.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.892 ±(99.9%) 3.988 ops/ms [Average]
  (min, avg, max) = (9.665, 9.892, 10.101), stdev = 0.219
  CI (99.9%): [5.904, 13.880] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.478 ops/ms
# Warmup Iteration   2: 7.716 ops/ms
# Warmup Iteration   3: 8.190 ops/ms
Iteration   1: 8.558 ops/ms
Iteration   2: 8.587 ops/ms
Iteration   3: 8.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.484 ±(99.9%) 2.820 ops/ms [Average]
  (min, avg, max) = (8.306, 8.484, 8.587), stdev = 0.155
  CI (99.9%): [5.664, 11.304] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.503 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.003 ms/op
Iteration   1: 3.164 ±(99.9%) 0.004 ms/op
Iteration   2: 3.430 ±(99.9%) 0.006 ms/op
Iteration   3: 3.281 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.292 ±(99.9%) 2.435 ms/op [Average]
  (min, avg, max) = (3.164, 3.292, 3.430), stdev = 0.133
  CI (99.9%): [0.857, 5.726] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.631 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
Iteration   3: 3.177 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.114 ±(99.9%) 1.004 ms/op [Average]
  (min, avg, max) = (3.076, 3.114, 3.177), stdev = 0.055
  CI (99.9%): [2.110, 4.118] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.383 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.515 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.001 ms/op
Iteration   1: 3.238 ±(99.9%) 0.004 ms/op
Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
Iteration   3: 3.231 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.204 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (3.142, 3.204, 3.238), stdev = 0.053
  CI (99.9%): [2.228, 4.179] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.631 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.007 ms/op
Iteration   1: 3.780 ±(99.9%) 0.011 ms/op
Iteration   2: 3.761 ±(99.9%) 0.006 ms/op
Iteration   3: 3.728 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.728, 3.756, 3.780), stdev = 0.026
  CI (99.9%): [3.275, 4.237] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.851 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.010 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  11.231 ms/op
                 createUser·p0.9999: 23.907 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.259 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  8.680 ms/op
                 createUser·p0.9999: 20.708 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300346
  mean =      3.197 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19644 
    [ 2.500,  5.000) = 274542 
    [ 5.000,  7.500) = 5264 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     14.740 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


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
# Warmup Iteration   1: 7.332 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.008 ms/op
Iteration   1: 3.253 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.401 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 20.001 ms/op
                 existUser·p1.00:   21.955 ms/op

Iteration   2: 3.122 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  11.903 ms/op
                 existUser·p0.9999: 27.460 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  9.724 ms/op
                 existUser·p0.9999: 33.620 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306105
  mean =      3.133 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18724 
    [ 2.500,  5.000) = 282843 
    [ 5.000,  7.500) = 3812 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     12.843 ms/op
     p(99.9900) =     31.810 ms/op
     p(99.9990) =     34.067 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 8.771 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.647 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.009 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.286 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  19.377 ms/op
                 getUser·p0.9999: 20.632 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   2: 3.388 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  20.691 ms/op
                 getUser·p0.9999: 23.763 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.535 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  12.005 ms/op
                 getUser·p0.9999: 22.452 ms/op
                 getUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286504
  mean =      3.350 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18837 
    [ 2.500,  5.000) = 257699 
    [ 5.000,  7.500) = 9101 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.286 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     17.350 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.711 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 9.065 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
Iteration   1: 3.757 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  14.218 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   2: 3.753 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.896 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 18.984 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.888 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.381 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252659
  mean =      3.798 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 84 
    [ 2.500,  5.000) = 244627 
    [ 5.000,  7.500) = 5687 
    [ 7.500, 10.000) = 1477 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.882 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.292 ms/op
     p(99.9900) =     19.521 ms/op
     p(99.9990) =     20.421 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.787 ± 3.620  ops/ms
ClientPb.existUser                       thrpt       3  10.577 ± 2.492  ops/ms
ClientPb.getUser                         thrpt       3   9.892 ± 3.988  ops/ms
ClientPb.listUser                        thrpt       3   8.484 ± 2.820  ops/ms
ClientPb.createUser                       avgt       3   3.292 ± 2.435   ms/op
ClientPb.existUser                        avgt       3   3.114 ± 1.004   ms/op
ClientPb.getUser                          avgt       3   3.204 ± 0.975   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 0.481   ms/op
ClientPb.createUser                     sample  300346   3.197 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.161           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.740           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.479           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.642           ms/op
ClientPb.existUser                      sample  306105   3.133 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.721           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.843           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.810           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  286504   3.350 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.350           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.069           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.035           ms/op
ClientPb.listUser                       sample  252659   3.798 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.882           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.695           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.258           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.292           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.521           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.644           ms/op
