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
# Warmup Iteration   1: 2.057 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 8.462 ops/ms
Iteration   1: 9.101 ops/ms
Iteration   2: 9.269 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.269 ±(99.9%) 3.057 ops/ms [Average]
  (min, avg, max) = (9.101, 9.269, 9.436), stdev = 0.168
  CI (99.9%): [6.212, 12.326] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.997 ops/ms
# Warmup Iteration   2: 8.512 ops/ms
# Warmup Iteration   3: 9.280 ops/ms
Iteration   1: 9.807 ops/ms
Iteration   2: 9.878 ops/ms
Iteration   3: 9.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.839 ±(99.9%) 0.655 ops/ms [Average]
  (min, avg, max) = (9.807, 9.839, 9.878), stdev = 0.036
  CI (99.9%): [9.184, 10.495] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.816 ops/ms
# Warmup Iteration   2: 8.144 ops/ms
# Warmup Iteration   3: 8.873 ops/ms
Iteration   1: 9.360 ops/ms
Iteration   2: 9.050 ops/ms
Iteration   3: 9.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.247 ±(99.9%) 3.129 ops/ms [Average]
  (min, avg, max) = (9.050, 9.247, 9.360), stdev = 0.172
  CI (99.9%): [6.118, 12.376] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.781 ops/ms
# Warmup Iteration   2: 7.199 ops/ms
# Warmup Iteration   3: 7.629 ops/ms
Iteration   1: 7.698 ops/ms
Iteration   2: 7.727 ops/ms
Iteration   3: 7.863 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.763 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (7.698, 7.763, 7.863), stdev = 0.088
  CI (99.9%): [6.155, 9.370] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.922 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.906 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.624 ±(99.9%) 0.004 ms/op
Iteration   1: 3.601 ±(99.9%) 0.005 ms/op
Iteration   2: 3.645 ±(99.9%) 0.006 ms/op
Iteration   3: 3.519 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.588 ±(99.9%) 1.170 ms/op [Average]
  (min, avg, max) = (3.519, 3.588, 3.645), stdev = 0.064
  CI (99.9%): [2.418, 4.759] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.609 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.309 ±(99.9%) 0.006 ms/op
Iteration   1: 3.333 ±(99.9%) 0.005 ms/op
Iteration   2: 3.359 ±(99.9%) 0.006 ms/op
Iteration   3: 3.240 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.311 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.240, 3.311, 3.359), stdev = 0.062
  CI (99.9%): [2.176, 4.445] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.093 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.006 ms/op
Iteration   1: 3.493 ±(99.9%) 0.004 ms/op
Iteration   2: 3.559 ±(99.9%) 0.004 ms/op
Iteration   3: 3.444 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.499 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.444, 3.499, 3.559), stdev = 0.058
  CI (99.9%): [2.448, 4.550] (assumes normal distribution)


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
# Warmup Iteration   1: 11.086 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.561 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.168 ±(99.9%) 0.007 ms/op
Iteration   1: 4.166 ±(99.9%) 0.007 ms/op
Iteration   2: 4.078 ±(99.9%) 0.004 ms/op
Iteration   3: 4.011 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.085 ±(99.9%) 1.422 ms/op [Average]
  (min, avg, max) = (4.011, 4.085, 4.166), stdev = 0.078
  CI (99.9%): [2.663, 5.507] (assumes normal distribution)


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
# Warmup Iteration   1: 12.184 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.339 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.802 ±(99.9%) 0.015 ms/op
Iteration   1: 3.411 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.767 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  18.292 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.529 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.067 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  19.310 ms/op
                 createUser·p0.9999: 25.131 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   3: 3.578 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.259 ms/op
                 createUser·p0.999:  21.070 ms/op
                 createUser·p0.9999: 27.167 ms/op
                 createUser·p1.00:   27.492 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273890
  mean =      3.504 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9346 
    [ 2.500,  5.000) = 256850 
    [ 5.000,  7.500) = 6407 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     19.369 ms/op
     p(99.9900) =     26.234 ms/op
     p(99.9990) =     27.435 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 9.638 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.483 ±(99.9%) 0.010 ms/op
Iteration   1: 3.415 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   6.250 ms/op
                 existUser·p0.999:  19.825 ms/op
                 existUser·p0.9999: 23.884 ms/op
                 existUser·p1.00:   24.478 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.503 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   5.915 ms/op
                 existUser·p0.999:  12.811 ms/op
                 existUser·p0.9999: 29.852 ms/op
                 existUser·p1.00:   31.064 ms/op

Iteration   3: 3.451 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  22.490 ms/op
                 existUser·p0.9999: 30.153 ms/op
                 existUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283506
  mean =      3.386 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11429 
    [ 2.500,  5.000) = 265869 
    [ 5.000,  7.500) = 4975 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     16.114 ms/op
     p(99.9900) =     29.840 ms/op
     p(99.9990) =     31.266 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 8.673 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.548 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   7.324 ms/op
                 getUser·p0.999:  19.634 ms/op
                 getUser·p0.9999: 24.605 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   2: 3.440 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.407 ms/op
                 getUser·p0.999:  21.824 ms/op
                 getUser·p0.9999: 25.107 ms/op
                 getUser·p1.00:   27.394 ms/op

Iteration   3: 3.517 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  12.927 ms/op
                 getUser·p0.9999: 26.199 ms/op
                 getUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275194
  mean =      3.487 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6289 
    [ 2.500,  5.000) = 260018 
    [ 5.000,  7.500) = 6939 
    [ 7.500, 10.000) = 1482 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     27.033 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 11.857 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.727 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.016 ms/op
Iteration   1: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  22.643 ms/op
                 listUser·p0.9999: 27.365 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   2: 4.082 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.915 ms/op
                 listUser·p0.99:   8.520 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 22.249 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 4.219 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.970 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.351 ms/op
                 listUser·p0.99:   8.339 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233011
  mean =      4.121 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 221634 
    [ 5.000,  7.500) = 7978 
    [ 7.500, 10.000) = 2354 
    [10.000, 12.500) = 406 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 215 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      8.249 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     25.703 ms/op
     p(99.9990) =     27.613 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.269 ± 3.057  ops/ms
ClientPb.existUser                       thrpt       3   9.839 ± 0.655  ops/ms
ClientPb.getUser                         thrpt       3   9.247 ± 3.129  ops/ms
ClientPb.listUser                        thrpt       3   7.763 ± 1.607  ops/ms
ClientPb.createUser                       avgt       3   3.588 ± 1.170   ms/op
ClientPb.existUser                        avgt       3   3.311 ± 1.135   ms/op
ClientPb.getUser                          avgt       3   3.499 ± 1.051   ms/op
ClientPb.listUser                         avgt       3   4.085 ± 1.422   ms/op
ClientPb.createUser                     sample  273890   3.504 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.011           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.369           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.234           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.492           ms/op
ClientPb.existUser                      sample  283506   3.386 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.913           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.358           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.964           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.114           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.840           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.834           ms/op
ClientPb.getUser                        sample  275194   3.487 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.257           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.996           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.943           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.494           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  233011   4.121 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.380           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.249           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.909           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.703           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.689           ms/op
