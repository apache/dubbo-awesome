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
# Warmup Iteration   1: 2.700 ops/ms
# Warmup Iteration   2: 6.928 ops/ms
# Warmup Iteration   3: 8.879 ops/ms
Iteration   1: 10.128 ops/ms
Iteration   2: 9.954 ops/ms
Iteration   3: 9.864 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.982 ±(99.9%) 2.456 ops/ms [Average]
  (min, avg, max) = (9.864, 9.982, 10.128), stdev = 0.135
  CI (99.9%): [7.526, 12.438] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.673 ops/ms
# Warmup Iteration   2: 8.880 ops/ms
# Warmup Iteration   3: 10.149 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.554 ops/ms
Iteration   3: 10.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.606 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (10.549, 10.606, 10.715), stdev = 0.094
  CI (99.9%): [8.883, 12.329] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.836 ops/ms
# Warmup Iteration   2: 9.513 ops/ms
# Warmup Iteration   3: 9.698 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.195 ops/ms
Iteration   3: 10.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.325 ±(99.9%) 3.190 ops/ms [Average]
  (min, avg, max) = (10.195, 10.325, 10.524), stdev = 0.175
  CI (99.9%): [7.135, 13.515] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.547 ops/ms
# Warmup Iteration   2: 7.781 ops/ms
# Warmup Iteration   3: 8.299 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.737 ops/ms
Iteration   3: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.554 ±(99.9%) 2.955 ops/ms [Average]
  (min, avg, max) = (8.428, 8.554, 8.737), stdev = 0.162
  CI (99.9%): [5.599, 11.509] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.176 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.005 ms/op
Iteration   1: 3.179 ±(99.9%) 0.007 ms/op
Iteration   2: 3.058 ±(99.9%) 0.005 ms/op
Iteration   3: 3.142 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.126 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (3.058, 3.126, 3.179), stdev = 0.062
  CI (99.9%): [1.990, 4.263] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.747 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.002 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
Iteration   3: 2.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.055 ±(99.9%) 1.359 ms/op [Average]
  (min, avg, max) = (2.969, 3.055, 3.101), stdev = 0.074
  CI (99.9%): [1.696, 4.414] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.503 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.381 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.002 ms/op
Iteration   1: 3.223 ±(99.9%) 0.005 ms/op
Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
Iteration   3: 3.335 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.221 ±(99.9%) 2.094 ms/op [Average]
  (min, avg, max) = (3.105, 3.221, 3.335), stdev = 0.115
  CI (99.9%): [1.127, 5.315] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.758 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.007 ms/op
Iteration   1: 3.675 ±(99.9%) 0.008 ms/op
Iteration   2: 3.666 ±(99.9%) 0.006 ms/op
Iteration   3: 3.681 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.674 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (3.666, 3.674, 3.681), stdev = 0.008
  CI (99.9%): [3.534, 3.814] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.690 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
Iteration   1: 3.109 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  11.829 ms/op
                 createUser·p0.9999: 20.110 ms/op
                 createUser·p1.00:   20.644 ms/op

Iteration   2: 3.125 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.427 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  10.863 ms/op
                 createUser·p0.9999: 25.642 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.404 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  16.623 ms/op
                 createUser·p0.9999: 19.849 ms/op
                 createUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307790
  mean =      3.118 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21068 
    [ 2.500,  5.000) = 282434 
    [ 5.000,  7.500) = 3515 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 164 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     15.916 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     26.043 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.895 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.162 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   5.218 ms/op
                 existUser·p0.999:  11.158 ms/op
                 existUser·p0.9999: 19.333 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  9.254 ms/op
                 existUser·p0.9999: 21.587 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 3.137 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   4.067 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  11.436 ms/op
                 existUser·p0.9999: 20.245 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308938
  mean =      3.103 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25349 
    [ 2.500,  5.000) = 278568 
    [ 5.000,  7.500) = 4246 
    [ 7.500, 10.000) = 417 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     11.158 ms/op
     p(99.9900) =     20.818 ms/op
     p(99.9990) =     21.818 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 7.812 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.387 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.010 ms/op
Iteration   1: 3.144 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  18.584 ms/op
                 getUser·p0.9999: 20.605 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 3.131 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.759 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   6.438 ms/op
                 getUser·p0.999:  10.204 ms/op
                 getUser·p0.9999: 21.266 ms/op
                 getUser·p1.00:   21.791 ms/op

Iteration   3: 3.310 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  14.816 ms/op
                 getUser·p0.9999: 20.436 ms/op
                 getUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300523
  mean =      3.193 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12240 
    [ 2.500,  5.000) = 280922 
    [ 5.000,  7.500) = 6056 
    [ 7.500, 10.000) = 787 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     15.269 ms/op
     p(99.9900) =     21.003 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 8.841 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.011 ms/op
Iteration   1: 3.761 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 21.462 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.741 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.907 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.477 ms/op
                 listUser·p0.9999: 15.883 ms/op
                 listUser·p1.00:   15.942 ms/op

Iteration   3: 3.760 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.671 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.574 ms/op
                 listUser·p0.999:  12.108 ms/op
                 listUser·p0.9999: 13.877 ms/op
                 listUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255673
  mean =      3.754 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 100 
    [ 2.500,  5.000) = 246129 
    [ 5.000,  7.500) = 7281 
    [ 7.500, 10.000) = 1355 
    [10.000, 12.500) = 473 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      7.195 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     20.279 ms/op
     p(99.9990) =     21.933 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.982 ± 2.456  ops/ms
ClientPb.existUser                       thrpt       3  10.606 ± 1.723  ops/ms
ClientPb.getUser                         thrpt       3  10.325 ± 3.190  ops/ms
ClientPb.listUser                        thrpt       3   8.554 ± 2.955  ops/ms
ClientPb.createUser                       avgt       3   3.126 ± 1.137   ms/op
ClientPb.existUser                        avgt       3   3.055 ± 1.359   ms/op
ClientPb.getUser                          avgt       3   3.221 ± 2.094   ms/op
ClientPb.listUser                         avgt       3   3.674 ± 0.140   ms/op
ClientPb.createUser                     sample  307790   3.118 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.640           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.276           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.916           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.347           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.116           ms/op
ClientPb.existUser                      sample  308938   3.103 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.158           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.818           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.118           ms/op
ClientPb.getUser                        sample  300523   3.193 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.907           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.332           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.269           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.003           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.791           ms/op
ClientPb.listUser                       sample  255673   3.754 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.579           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.039           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.195           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.279           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.348           ms/op
