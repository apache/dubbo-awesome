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
# Warmup Iteration   1: 2.486 ops/ms
# Warmup Iteration   2: 5.660 ops/ms
# Warmup Iteration   3: 9.426 ops/ms
Iteration   1: 9.752 ops/ms
Iteration   2: 9.519 ops/ms
Iteration   3: 9.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.639 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (9.519, 9.639, 9.752), stdev = 0.117
  CI (99.9%): [7.509, 11.770] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.774 ops/ms
# Warmup Iteration   2: 9.134 ops/ms
# Warmup Iteration   3: 9.826 ops/ms
Iteration   1: 10.108 ops/ms
Iteration   2: 10.257 ops/ms
Iteration   3: 9.865 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.077 ±(99.9%) 3.612 ops/ms [Average]
  (min, avg, max) = (9.865, 10.077, 10.257), stdev = 0.198
  CI (99.9%): [6.465, 13.689] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 8.830 ops/ms
# Warmup Iteration   3: 9.728 ops/ms
Iteration   1: 9.700 ops/ms
Iteration   2: 9.654 ops/ms
Iteration   3: 9.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.708 ±(99.9%) 1.078 ops/ms [Average]
  (min, avg, max) = (9.654, 9.708, 9.771), stdev = 0.059
  CI (99.9%): [8.631, 10.786] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 7.558 ops/ms
# Warmup Iteration   3: 8.517 ops/ms
Iteration   1: 8.509 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.518 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.444 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (8.306, 8.444, 8.518), stdev = 0.120
  CI (99.9%): [6.261, 10.628] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.368 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.003 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
Iteration   2: 3.146 ±(99.9%) 0.003 ms/op
Iteration   3: 3.150 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 1.042 ms/op [Average]
  (min, avg, max) = (3.146, 3.181, 3.247), stdev = 0.057
  CI (99.9%): [2.139, 4.223] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.085 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.004 ms/op
Iteration   1: 3.039 ±(99.9%) 0.007 ms/op
Iteration   2: 3.043 ±(99.9%) 0.004 ms/op
Iteration   3: 3.019 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.033 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.019, 3.033, 3.043), stdev = 0.013
  CI (99.9%): [2.795, 3.271] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.070 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.003 ms/op
Iteration   1: 3.164 ±(99.9%) 0.005 ms/op
Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
Iteration   3: 3.166 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.127 ±(99.9%) 1.209 ms/op [Average]
  (min, avg, max) = (3.050, 3.127, 3.166), stdev = 0.066
  CI (99.9%): [1.918, 4.336] (assumes normal distribution)


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
# Warmup Iteration   1: 9.274 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.006 ms/op
Iteration   1: 3.793 ±(99.9%) 0.007 ms/op
Iteration   2: 3.717 ±(99.9%) 0.010 ms/op
Iteration   3: 3.708 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (3.708, 3.739, 3.793), stdev = 0.046
  CI (99.9%): [2.891, 4.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.208 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.334 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  8.595 ms/op
                 createUser·p0.9999: 23.944 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.096 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.228 ms/op
                 createUser·p0.95:   3.322 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  14.975 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302416
  mean =      3.172 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21806 
    [ 2.500,  5.000) = 274523 
    [ 5.000,  7.500) = 5310 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     16.600 ms/op
     p(99.9900) =     24.576 ms/op
     p(99.9990) =     25.558 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 7.674 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.007 ms/op
Iteration   1: 3.193 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.196 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 20.971 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  10.867 ms/op
                 existUser·p0.9999: 28.349 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.333 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  14.621 ms/op
                 existUser·p0.9999: 22.905 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293825
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29343 
    [ 2.500,  5.000) = 256589 
    [ 5.000,  7.500) = 7046 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     12.133 ms/op
     p(99.9900) =     26.693 ms/op
     p(99.9990) =     28.596 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 7.299 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.551 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.227 ±(99.9%) 0.009 ms/op
Iteration   1: 3.266 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.217 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.517 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 23.613 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  12.009 ms/op
                 getUser·p0.9999: 25.361 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.283 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.313 ms/op
                 getUser·p0.999:  12.576 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293189
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10017 
    [ 2.500,  5.000) = 276590 
    [ 5.000,  7.500) = 5489 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 153 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     24.253 ms/op
     p(99.9990) =     26.083 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.533 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.269 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.011 ms/op
Iteration   1: 4.100 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  16.380 ms/op
                 listUser·p0.9999: 20.734 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.869 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.237 ms/op
                 listUser·p0.9999: 19.249 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.705 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.433 ms/op
                 listUser·p0.9999: 15.368 ms/op
                 listUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 247174
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 81 
    [ 2.500,  5.000) = 235980 
    [ 5.000,  7.500) = 8071 
    [ 7.500, 10.000) = 2201 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     19.417 ms/op
     p(99.9990) =     21.286 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.639 ± 2.130  ops/ms
ClientPb.existUser                       thrpt       3  10.077 ± 3.612  ops/ms
ClientPb.getUser                         thrpt       3   9.708 ± 1.078  ops/ms
ClientPb.listUser                        thrpt       3   8.444 ± 2.183  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 1.042   ms/op
ClientPb.existUser                        avgt       3   3.033 ± 0.238   ms/op
ClientPb.getUser                          avgt       3   3.127 ± 1.209   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 0.848   ms/op
ClientPb.createUser                     sample  302416   3.172 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.983           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.457           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.600           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.576           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018           ms/op
ClientPb.existUser                      sample  293825   3.267 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.333           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.203           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.654           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.133           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.693           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.474           ms/op
ClientPb.getUser                        sample  293189   3.273 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.000           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.654           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.751           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.009           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.253           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  247174   3.885 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.715           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.758           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.926           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.417           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.398           ms/op
