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
# Warmup Iteration   1: 2.524 ops/ms
# Warmup Iteration   2: 6.065 ops/ms
# Warmup Iteration   3: 9.321 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 9.580 ops/ms
Iteration   3: 9.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.629 ±(99.9%) 3.628 ops/ms [Average]
  (min, avg, max) = (9.459, 9.629, 9.848), stdev = 0.199
  CI (99.9%): [6.001, 13.257] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ops/ms
# Warmup Iteration   2: 9.953 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.506 ops/ms
Iteration   2: 10.620 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.550 ±(99.9%) 1.126 ops/ms [Average]
  (min, avg, max) = (10.506, 10.550, 10.620), stdev = 0.062
  CI (99.9%): [9.424, 11.676] (assumes normal distribution)


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
# Warmup Iteration   1: 3.768 ops/ms
# Warmup Iteration   2: 8.714 ops/ms
# Warmup Iteration   3: 9.335 ops/ms
Iteration   1: 10.463 ops/ms
Iteration   2: 10.586 ops/ms
Iteration   3: 10.323 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.457 ±(99.9%) 2.409 ops/ms [Average]
  (min, avg, max) = (10.323, 10.457, 10.586), stdev = 0.132
  CI (99.9%): [8.048, 12.866] (assumes normal distribution)


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
# Warmup Iteration   1: 3.387 ops/ms
# Warmup Iteration   2: 7.359 ops/ms
# Warmup Iteration   3: 8.313 ops/ms
Iteration   1: 8.673 ops/ms
Iteration   2: 8.377 ops/ms
Iteration   3: 8.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.564 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (8.377, 8.564, 8.673), stdev = 0.163
  CI (99.9%): [5.588, 11.541] (assumes normal distribution)


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
# Warmup Iteration   1: 8.496 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.005 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op
Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
Iteration   3: 3.146 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.153 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (3.122, 3.153, 3.192), stdev = 0.035
  CI (99.9%): [2.511, 3.796] (assumes normal distribution)


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
# Warmup Iteration   1: 8.482 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.006 ms/op
Iteration   1: 3.254 ±(99.9%) 0.007 ms/op
Iteration   2: 3.586 ±(99.9%) 0.007 ms/op
Iteration   3: 3.009 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.283 ±(99.9%) 5.277 ms/op [Average]
  (min, avg, max) = (3.009, 3.283, 3.586), stdev = 0.289
  CI (99.9%): [≈ 0, 8.560] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.346 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.002 ms/op
Iteration   1: 3.213 ±(99.9%) 0.007 ms/op
Iteration   2: 3.321 ±(99.9%) 0.006 ms/op
Iteration   3: 3.192 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.242 ±(99.9%) 1.255 ms/op [Average]
  (min, avg, max) = (3.192, 3.242, 3.321), stdev = 0.069
  CI (99.9%): [1.987, 4.497] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.603 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.004 ms/op
Iteration   1: 3.879 ±(99.9%) 0.006 ms/op
Iteration   2: 3.746 ±(99.9%) 0.006 ms/op
Iteration   3: 3.700 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.775 ±(99.9%) 1.692 ms/op [Average]
  (min, avg, max) = (3.700, 3.775, 3.879), stdev = 0.093
  CI (99.9%): [2.083, 5.467] (assumes normal distribution)


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
# Warmup Iteration   1: 7.333 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.640 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  13.542 ms/op
                 createUser·p0.9999: 21.430 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   2: 3.348 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.542 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  18.499 ms/op
                 createUser·p0.9999: 24.230 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  15.326 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295658
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20775 
    [ 2.500,  5.000) = 268718 
    [ 5.000,  7.500) = 5037 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     16.107 ms/op
     p(99.9900) =     22.620 ms/op
     p(99.9990) =     24.711 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 7.998 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.010 ms/op
Iteration   1: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  10.129 ms/op
                 existUser·p0.9999: 30.933 ms/op
                 existUser·p1.00:   30.966 ms/op

Iteration   2: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  13.074 ms/op
                 existUser·p0.9999: 20.214 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 3.128 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.953 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  7.999 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301115
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28439 
    [ 2.500,  5.000) = 268438 
    [ 5.000,  7.500) = 3624 
    [ 7.500, 10.000) = 245 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 123 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.926 ms/op
     p(99.9900) =     29.848 ms/op
     p(99.9990) =     30.966 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


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
# Warmup Iteration   1: 7.455 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.009 ms/op
Iteration   1: 3.457 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   5.202 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  18.594 ms/op
                 getUser·p0.9999: 23.019 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   2: 3.236 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.473 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  16.226 ms/op
                 getUser·p0.9999: 25.362 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 3.314 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.382 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.182 ms/op
                 getUser·p0.999:  13.267 ms/op
                 getUser·p0.9999: 28.979 ms/op
                 getUser·p1.00:   30.769 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287876
  mean =      3.333 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12900 
    [ 2.500,  5.000) = 265037 
    [ 5.000,  7.500) = 8832 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     17.736 ms/op
     p(99.9900) =     28.325 ms/op
     p(99.9990) =     30.646 ms/op
     p(99.9999) =     30.769 ms/op
    p(100.0000) =     30.769 ms/op


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
# Warmup Iteration   1: 10.170 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.013 ms/op
Iteration   1: 4.078 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.919 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   6.247 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  21.332 ms/op
                 listUser·p0.9999: 35.924 ms/op
                 listUser·p1.00:   36.438 ms/op

Iteration   2: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.032 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 15.709 ms/op
                 listUser·p1.00:   16.122 ms/op

Iteration   3: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.355 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  15.057 ms/op
                 listUser·p0.9999: 19.300 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240360
  mean =      3.992 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 228116 
    [ 5.000,  7.500) = 9065 
    [ 7.500, 10.000) = 2183 
    [10.000, 12.500) = 365 
    [12.500, 15.000) = 267 
    [15.000, 17.500) = 160 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.919 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     15.352 ms/op
     p(99.9900) =     35.389 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.629 ± 3.628  ops/ms
ClientPb.existUser                       thrpt       3  10.550 ± 1.126  ops/ms
ClientPb.getUser                         thrpt       3  10.457 ± 2.409  ops/ms
ClientPb.listUser                        thrpt       3   8.564 ± 2.977  ops/ms
ClientPb.createUser                       avgt       3   3.153 ± 0.642   ms/op
ClientPb.existUser                        avgt       3   3.283 ± 5.277   ms/op
ClientPb.getUser                          avgt       3   3.242 ± 1.255   ms/op
ClientPb.listUser                         avgt       3   3.775 ± 1.692   ms/op
ClientPb.createUser                     sample  295658   3.244 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.107           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.620           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.871           ms/op
ClientPb.existUser                      sample  301115   3.186 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.926           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.848           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.966           ms/op
ClientPb.getUser                        sample  287876   3.333 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.049           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.547           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.234           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.736           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.325           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.769           ms/op
ClientPb.listUser                       sample  240360   3.992 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.038           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.352           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.389           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.438           ms/op
