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
# Warmup Iteration   1: 2.399 ops/ms
# Warmup Iteration   2: 6.337 ops/ms
# Warmup Iteration   3: 9.002 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.924 ops/ms
Iteration   3: 9.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.689 ±(99.9%) 3.713 ops/ms [Average]
  (min, avg, max) = (9.563, 9.689, 9.924), stdev = 0.204
  CI (99.9%): [5.976, 13.402] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.543 ops/ms
# Warmup Iteration   2: 8.804 ops/ms
# Warmup Iteration   3: 9.934 ops/ms
Iteration   1: 10.336 ops/ms
Iteration   2: 10.291 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.282 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (10.219, 10.282, 10.336), stdev = 0.059
  CI (99.9%): [9.203, 11.361] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 9.719 ops/ms
Iteration   1: 9.774 ops/ms
Iteration   2: 9.621 ops/ms
Iteration   3: 10.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.815 ±(99.9%) 3.976 ops/ms [Average]
  (min, avg, max) = (9.621, 9.815, 10.051), stdev = 0.218
  CI (99.9%): [5.839, 13.792] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.419 ops/ms
# Warmup Iteration   2: 7.594 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.508 ops/ms
Iteration   2: 8.499 ops/ms
Iteration   3: 8.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.463 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (8.381, 8.463, 8.508), stdev = 0.071
  CI (99.9%): [7.169, 9.757] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.080 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.722 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.006 ms/op
Iteration   1: 3.402 ±(99.9%) 0.007 ms/op
Iteration   2: 3.252 ±(99.9%) 0.005 ms/op
Iteration   3: 3.373 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.342 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.252, 3.342, 3.402), stdev = 0.079
  CI (99.9%): [1.896, 4.789] (assumes normal distribution)


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
# Warmup Iteration   1: 6.737 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.003 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.145 ±(99.9%) 0.007 ms/op
Iteration   3: 3.290 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.210 ±(99.9%) 1.339 ms/op [Average]
  (min, avg, max) = (3.145, 3.210, 3.290), stdev = 0.073
  CI (99.9%): [1.871, 4.549] (assumes normal distribution)


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
# Warmup Iteration   1: 8.084 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.005 ms/op
Iteration   1: 3.206 ±(99.9%) 0.002 ms/op
Iteration   2: 3.207 ±(99.9%) 0.004 ms/op
Iteration   3: 3.241 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.218 ±(99.9%) 0.358 ms/op [Average]
  (min, avg, max) = (3.206, 3.218, 3.241), stdev = 0.020
  CI (99.9%): [2.860, 3.576] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.321 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.006 ms/op
Iteration   1: 3.920 ±(99.9%) 0.006 ms/op
Iteration   2: 3.780 ±(99.9%) 0.008 ms/op
Iteration   3: 3.824 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.841 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.780, 3.841, 3.920), stdev = 0.072
  CI (99.9%): [2.536, 5.147] (assumes normal distribution)


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
# Warmup Iteration   1: 8.447 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.290 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   6.554 ms/op
                 createUser·p0.999:  16.833 ms/op
                 createUser·p0.9999: 19.375 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   2: 3.258 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.567 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  10.120 ms/op
                 createUser·p0.9999: 21.447 ms/op
                 createUser·p1.00:   22.184 ms/op

Iteration   3: 3.268 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.110 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  15.270 ms/op
                 createUser·p0.9999: 21.165 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293349
  mean =      3.272 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23768 
    [ 2.500,  5.000) = 262283 
    [ 5.000,  7.500) = 6074 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     15.536 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     21.992 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.438 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.494 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.267 ±(99.9%) 0.009 ms/op
Iteration   1: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  11.325 ms/op
                 existUser·p0.9999: 22.172 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  9.560 ms/op
                 existUser·p0.9999: 24.112 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   3: 3.381 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  15.516 ms/op
                 existUser·p0.9999: 24.725 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 292787
  mean =      3.275 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16939 
    [ 2.500,  5.000) = 268282 
    [ 5.000,  7.500) = 6362 
    [ 7.500, 10.000) = 832 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     11.636 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 9.044 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.370 ±(99.9%) 0.011 ms/op
Iteration   1: 3.393 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  18.465 ms/op
                 getUser·p0.9999: 20.976 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.264 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  10.599 ms/op
                 getUser·p0.9999: 22.479 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.587 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  11.590 ms/op
                 getUser·p0.9999: 22.430 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291954
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16882 
    [ 2.500,  5.000) = 264910 
    [ 5.000,  7.500) = 8798 
    [ 7.500, 10.000) = 1027 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 166 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     11.657 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.465 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 9.563 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.911 ±(99.9%) 0.014 ms/op
Iteration   1: 3.783 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.069 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   7.790 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 20.563 ms/op
                 listUser·p1.00:   21.234 ms/op

Iteration   2: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.092 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   7.340 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.809 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  14.812 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253702
  mean =      3.782 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 246167 
    [ 5.000,  7.500) = 4995 
    [ 7.500, 10.000) = 1710 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     14.390 ms/op
     p(99.9900) =     18.731 ms/op
     p(99.9990) =     20.790 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.689 ± 3.713  ops/ms
ClientPb.existUser                       thrpt       3  10.282 ± 1.079  ops/ms
ClientPb.getUser                         thrpt       3   9.815 ± 3.976  ops/ms
ClientPb.listUser                        thrpt       3   8.463 ± 1.294  ops/ms
ClientPb.createUser                       avgt       3   3.342 ± 1.446   ms/op
ClientPb.existUser                        avgt       3   3.210 ± 1.339   ms/op
ClientPb.getUser                          avgt       3   3.218 ± 0.358   ms/op
ClientPb.listUser                         avgt       3   3.841 ± 1.305   ms/op
ClientPb.createUser                     sample  293349   3.272 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.110           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.536           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.168           ms/op
ClientPb.createUser:createUser·p1.00    sample          22.184           ms/op
ClientPb.existUser                      sample  292787   3.275 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.690           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.887           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.293           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.636           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.019           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.199           ms/op
ClientPb.getUser                        sample  291954   3.287 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.748           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.128           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.657           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.282           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.691           ms/op
ClientPb.listUser                       sample  253702   3.782 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.112           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.390           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.731           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.234           ms/op
