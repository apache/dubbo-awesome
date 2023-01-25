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
# Warmup Iteration   1: 2.556 ops/ms
# Warmup Iteration   2: 5.876 ops/ms
# Warmup Iteration   3: 9.110 ops/ms
Iteration   1: 9.650 ops/ms
Iteration   2: 10.153 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.909 ±(99.9%) 4.599 ops/ms [Average]
  (min, avg, max) = (9.650, 9.909, 10.153), stdev = 0.252
  CI (99.9%): [5.310, 14.508] (assumes normal distribution)


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
# Warmup Iteration   1: 3.500 ops/ms
# Warmup Iteration   2: 9.471 ops/ms
# Warmup Iteration   3: 10.578 ops/ms
Iteration   1: 10.371 ops/ms
Iteration   2: 10.188 ops/ms
Iteration   3: 10.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.247 ±(99.9%) 1.955 ops/ms [Average]
  (min, avg, max) = (10.183, 10.247, 10.371), stdev = 0.107
  CI (99.9%): [8.293, 12.202] (assumes normal distribution)


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
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 8.402 ops/ms
# Warmup Iteration   3: 9.741 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 10.136 ops/ms
Iteration   3: 10.422 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.244 ±(99.9%) 2.840 ops/ms [Average]
  (min, avg, max) = (10.136, 10.244, 10.422), stdev = 0.156
  CI (99.9%): [7.403, 13.084] (assumes normal distribution)


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
# Warmup Iteration   1: 2.974 ops/ms
# Warmup Iteration   2: 7.725 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.871 ops/ms
Iteration   2: 8.726 ops/ms
Iteration   3: 8.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.734 ±(99.9%) 2.439 ops/ms [Average]
  (min, avg, max) = (8.604, 8.734, 8.871), stdev = 0.134
  CI (99.9%): [6.295, 11.173] (assumes normal distribution)


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
# Warmup Iteration   1: 8.471 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.497 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.004 ms/op
Iteration   1: 3.362 ±(99.9%) 0.006 ms/op
Iteration   2: 3.116 ±(99.9%) 0.006 ms/op
Iteration   3: 3.275 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.251 ±(99.9%) 2.275 ms/op [Average]
  (min, avg, max) = (3.116, 3.251, 3.362), stdev = 0.125
  CI (99.9%): [0.976, 5.526] (assumes normal distribution)


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
# Warmup Iteration   1: 6.532 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.197 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.009 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 2.972 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.041 ±(99.9%) 1.662 ms/op [Average]
  (min, avg, max) = (2.972, 3.041, 3.144), stdev = 0.091
  CI (99.9%): [1.378, 4.703] (assumes normal distribution)


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
# Warmup Iteration   1: 6.699 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.273 ±(99.9%) 0.008 ms/op
Iteration   1: 3.210 ±(99.9%) 0.003 ms/op
Iteration   2: 3.376 ±(99.9%) 0.005 ms/op
Iteration   3: 3.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.223 ±(99.9%) 2.676 ms/op [Average]
  (min, avg, max) = (3.084, 3.223, 3.376), stdev = 0.147
  CI (99.9%): [0.548, 5.899] (assumes normal distribution)


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
# Warmup Iteration   1: 9.054 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.007 ms/op
Iteration   1: 3.774 ±(99.9%) 0.009 ms/op
Iteration   2: 3.801 ±(99.9%) 0.007 ms/op
Iteration   3: 3.704 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.760 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.704, 3.760, 3.801), stdev = 0.050
  CI (99.9%): [2.849, 4.671] (assumes normal distribution)


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
# Warmup Iteration   1: 7.416 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.009 ms/op
Iteration   1: 3.243 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.053 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  12.420 ms/op
                 createUser·p0.9999: 24.773 ms/op
                 createUser·p1.00:   25.166 ms/op

Iteration   2: 3.300 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  14.273 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.151 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.262 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  18.858 ms/op
                 createUser·p0.9999: 23.490 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296998
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22636 
    [ 2.500,  5.000) = 268163 
    [ 5.000,  7.500) = 5308 
    [ 7.500, 10.000) = 442 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.262 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     24.248 ms/op
     p(99.9990) =     25.366 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 7.837 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.042 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.286 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  10.240 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.161 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.382 ms/op
                 existUser·p0.9999: 35.521 ms/op
                 existUser·p1.00:   38.339 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 23.440 ms/op
                 existUser·p1.00:   24.084 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 309537
  mean =      3.097 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17086 
    [ 2.500,  5.000) = 287082 
    [ 5.000,  7.500) = 4794 
    [ 7.500, 10.000) = 260 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     34.278 ms/op
     p(99.9990) =     36.235 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 7.464 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.010 ms/op
Iteration   1: 3.245 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 20.921 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.160 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  19.438 ms/op
                 getUser·p0.9999: 28.275 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  14.321 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299582
  mean =      3.202 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16754 
    [ 2.500,  5.000) = 275813 
    [ 5.000,  7.500) = 5952 
    [ 7.500, 10.000) = 664 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     26.209 ms/op
     p(99.9990) =     28.870 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 8.347 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.767 ±(99.9%) 0.010 ms/op
Iteration   1: 3.753 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.954 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 20.757 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.740 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.390 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 18.037 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 3.730 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.157 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  13.707 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256321
  mean =      3.741 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 247333 
    [ 5.000,  7.500) = 6966 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 364 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.142 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     19.807 ms/op
     p(99.9990) =     22.995 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.909 ± 4.599  ops/ms
ClientPb.existUser                       thrpt       3  10.247 ± 1.955  ops/ms
ClientPb.getUser                         thrpt       3  10.244 ± 2.840  ops/ms
ClientPb.listUser                        thrpt       3   8.734 ± 2.439  ops/ms
ClientPb.createUser                       avgt       3   3.251 ± 2.275   ms/op
ClientPb.existUser                        avgt       3   3.041 ± 1.662   ms/op
ClientPb.getUser                          avgt       3   3.223 ± 2.676   ms/op
ClientPb.listUser                         avgt       3   3.760 ± 0.911   ms/op
ClientPb.createUser                     sample  296998   3.230 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.262           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.030           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.399           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.285           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.248           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.559           ms/op
ClientPb.existUser                      sample  309537   3.097 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.950           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.325           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.273           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.278           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  299582   3.202 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.190           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.576           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.209           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.196           ms/op
ClientPb.listUser                       sample  256321   3.741 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.142           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.629           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.254           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.807           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.200           ms/op
