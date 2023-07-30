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
# Warmup Iteration   1: 1.577 ops/ms
# Warmup Iteration   2: 3.166 ops/ms
# Warmup Iteration   3: 6.774 ops/ms
Iteration   1: 6.547 ops/ms
Iteration   2: 7.770 ops/ms
Iteration   3: 7.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.377 ±(99.9%) 13.123 ops/ms [Average]
  (min, avg, max) = (6.547, 7.377, 7.814), stdev = 0.719
  CI (99.9%): [≈ 0, 20.500] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.991 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 7.887 ops/ms
Iteration   1: 7.956 ops/ms
Iteration   2: 8.206 ops/ms
Iteration   3: 8.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.108 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (7.956, 8.108, 8.206), stdev = 0.134
  CI (99.9%): [5.670, 10.546] (assumes normal distribution)


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
# Warmup Iteration   1: 2.121 ops/ms
# Warmup Iteration   2: 5.716 ops/ms
# Warmup Iteration   3: 7.111 ops/ms
Iteration   1: 7.712 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.906 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (7.712, 7.906, 8.029), stdev = 0.170
  CI (99.9%): [4.803, 11.008] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.093 ops/ms
# Warmup Iteration   2: 5.008 ops/ms
# Warmup Iteration   3: 6.521 ops/ms
Iteration   1: 6.198 ops/ms
Iteration   2: 6.407 ops/ms
Iteration   3: 7.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.538 ±(99.9%) 7.699 ops/ms [Average]
  (min, avg, max) = (6.198, 6.538, 7.010), stdev = 0.422
  CI (99.9%): [≈ 0, 14.237] (assumes normal distribution)


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
# Warmup Iteration   1: 13.415 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.684 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.242 ±(99.9%) 0.012 ms/op
Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
Iteration   2: 4.124 ±(99.9%) 0.009 ms/op
Iteration   3: 4.056 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.083 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (4.056, 4.083, 4.124), stdev = 0.036
  CI (99.9%): [3.423, 4.744] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 13.034 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.701 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.005 ms/op
Iteration   1: 3.892 ±(99.9%) 0.008 ms/op
Iteration   2: 4.260 ±(99.9%) 0.003 ms/op
Iteration   3: 4.084 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.079 ±(99.9%) 3.355 ms/op [Average]
  (min, avg, max) = (3.892, 4.079, 4.260), stdev = 0.184
  CI (99.9%): [0.723, 7.434] (assumes normal distribution)


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
# Warmup Iteration   1: 12.580 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.234 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.467 ±(99.9%) 0.007 ms/op
Iteration   1: 4.148 ±(99.9%) 0.012 ms/op
Iteration   2: 4.187 ±(99.9%) 0.010 ms/op
Iteration   3: 3.985 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.107 ±(99.9%) 1.960 ms/op [Average]
  (min, avg, max) = (3.985, 4.107, 4.187), stdev = 0.107
  CI (99.9%): [2.147, 6.066] (assumes normal distribution)


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
# Warmup Iteration   1: 14.282 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.905 ±(99.9%) 0.006 ms/op
Iteration   1: 4.837 ±(99.9%) 0.015 ms/op
Iteration   2: 4.694 ±(99.9%) 0.020 ms/op
Iteration   3: 4.784 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.771 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (4.694, 4.771, 4.837), stdev = 0.072
  CI (99.9%): [3.452, 6.090] (assumes normal distribution)


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
# Warmup Iteration   1: 14.944 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.674 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.525 ±(99.9%) 0.019 ms/op
Iteration   1: 4.176 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.604 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   8.081 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 26.380 ms/op
                 createUser·p1.00:   26.771 ms/op

Iteration   2: 4.148 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.888 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   4.784 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.857 ms/op
                 createUser·p0.999:  27.807 ms/op
                 createUser·p0.9999: 34.734 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   3: 4.077 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.964 ms/op
                 createUser·p0.50:   3.875 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   6.685 ms/op
                 createUser·p0.999:  12.222 ms/op
                 createUser·p0.9999: 31.322 ms/op
                 createUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232101
  mean =      4.133 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 217 
    [ 2.500,  5.000) = 216242 
    [ 5.000,  7.500) = 13623 
    [ 7.500, 10.000) = 1387 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     32.597 ms/op
     p(99.9990) =     35.088 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 13.359 ±(99.9%) 0.183 ms/op
# Warmup Iteration   2: 4.988 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.142 ±(99.9%) 0.014 ms/op
Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.905 ms/op
                 existUser·p0.50:   3.834 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  13.042 ms/op
                 existUser·p0.9999: 30.279 ms/op
                 existUser·p1.00:   33.063 ms/op

Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.946 ms/op
                 existUser·p0.999:  12.643 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 3.960 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.659 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   7.422 ms/op
                 existUser·p0.999:  27.132 ms/op
                 existUser·p0.9999: 32.992 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 238246
  mean =      4.028 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 178 
    [ 2.500,  5.000) = 223958 
    [ 5.000,  7.500) = 11358 
    [ 7.500, 10.000) = 2080 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     15.283 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 14.508 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 5.304 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.331 ±(99.9%) 0.016 ms/op
Iteration   1: 4.188 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.424 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  16.318 ms/op
                 getUser·p0.9999: 30.817 ms/op
                 getUser·p1.00:   31.785 ms/op

Iteration   2: 4.104 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.286 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.858 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   7.905 ms/op
                 getUser·p0.999:  25.528 ms/op
                 getUser·p0.9999: 30.535 ms/op
                 getUser·p1.00:   31.195 ms/op

Iteration   3: 4.007 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.591 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.669 ms/op
                 getUser·p0.99:   6.898 ms/op
                 getUser·p0.999:  11.126 ms/op
                 getUser·p0.9999: 32.048 ms/op
                 getUser·p1.00:   32.768 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234209
  mean =      4.098 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 218686 
    [ 5.000,  7.500) = 11505 
    [ 7.500, 10.000) = 3142 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     30.933 ms/op
     p(99.9990) =     32.604 ms/op
     p(99.9999) =     32.768 ms/op
    p(100.0000) =     32.768 ms/op


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
# Warmup Iteration   1: 16.362 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 6.670 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.089 ±(99.9%) 0.020 ms/op
Iteration   1: 4.844 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  30.409 ms/op
                 listUser·p0.9999: 41.183 ms/op
                 listUser·p1.00:   42.009 ms/op

Iteration   2: 4.935 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.548 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  20.579 ms/op
                 listUser·p0.9999: 28.213 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   3: 4.806 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.456 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  19.005 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197400
  mean =      4.861 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 154061 
    [ 5.000, 10.000) = 42167 
    [10.000, 15.000) = 749 
    [15.000, 20.000) = 168 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 117 
    [30.000, 35.000) = 43 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.714 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      8.995 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     40.470 ms/op
     p(99.9990) =     41.562 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3   7.377 ± 13.123  ops/ms
ClientPb.existUser                       thrpt       3   8.108 ±  2.438  ops/ms
ClientPb.getUser                         thrpt       3   7.906 ±  3.103  ops/ms
ClientPb.listUser                        thrpt       3   6.538 ±  7.699  ops/ms
ClientPb.createUser                       avgt       3   4.083 ±  0.661   ms/op
ClientPb.existUser                        avgt       3   4.079 ±  3.355   ms/op
ClientPb.getUser                          avgt       3   4.107 ±  1.960   ms/op
ClientPb.listUser                         avgt       3   4.771 ±  1.319   ms/op
ClientPb.createUser                     sample  232101   4.133 ±  0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.604            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.985            ms/op
ClientPb.createUser:createUser·p0.90    sample           4.768            ms/op
ClientPb.createUser:createUser·p0.95    sample           5.202            ms/op
ClientPb.createUser:createUser·p0.99    sample           7.135            ms/op
ClientPb.createUser:createUser·p0.999   sample          17.203            ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.597            ms/op
ClientPb.createUser:createUser·p1.00    sample          35.521            ms/op
ClientPb.existUser                      sample  238246   4.028 ±  0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.659            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.858            ms/op
ClientPb.existUser:existUser·p0.90      sample           4.579            ms/op
ClientPb.existUser:existUser·p0.95      sample           5.186            ms/op
ClientPb.existUser:existUser·p0.99      sample           7.807            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.283            ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.605            ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127            ms/op
ClientPb.getUser                        sample  234209   4.098 ±  0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.424            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.895            ms/op
ClientPb.getUser:getUser·p0.90          sample           4.686            ms/op
ClientPb.getUser:getUser·p0.95          sample           5.308            ms/op
ClientPb.getUser:getUser·p0.99          sample           8.020            ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105            ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.933            ms/op
ClientPb.getUser:getUser·p1.00          sample          32.768            ms/op
ClientPb.listUser                       sample  197400   4.861 ±  0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.714            ms/op
ClientPb.listUser:listUser·p0.50        sample           4.661            ms/op
ClientPb.listUser:listUser·p0.90        sample           5.349            ms/op
ClientPb.listUser:listUser·p0.95        sample           5.988            ms/op
ClientPb.listUser:listUser·p0.99        sample           8.995            ms/op
ClientPb.listUser:listUser·p0.999       sample          24.740            ms/op
ClientPb.listUser:listUser·p0.9999      sample          40.470            ms/op
ClientPb.listUser:listUser·p1.00        sample          42.009            ms/op
