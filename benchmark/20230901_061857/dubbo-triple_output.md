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
# Warmup Iteration   1: 1.767 ops/ms
# Warmup Iteration   2: 3.693 ops/ms
# Warmup Iteration   3: 7.398 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 8.173 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.041 ±(99.9%) 2.876 ops/ms [Average]
  (min, avg, max) = (7.866, 8.041, 8.173), stdev = 0.158
  CI (99.9%): [5.165, 10.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.083 ops/ms
# Warmup Iteration   2: 6.514 ops/ms
# Warmup Iteration   3: 8.097 ops/ms
Iteration   1: 8.458 ops/ms
Iteration   2: 8.598 ops/ms
Iteration   3: 8.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.499 ±(99.9%) 1.574 ops/ms [Average]
  (min, avg, max) = (8.441, 8.499, 8.598), stdev = 0.086
  CI (99.9%): [6.926, 10.073] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.225 ops/ms
# Warmup Iteration   2: 6.105 ops/ms
# Warmup Iteration   3: 7.763 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.263 ops/ms
Iteration   3: 8.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.236 ±(99.9%) 1.929 ops/ms [Average]
  (min, avg, max) = (8.120, 8.236, 8.326), stdev = 0.106
  CI (99.9%): [6.307, 10.165] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
# Warmup Iteration   2: 5.736 ops/ms
# Warmup Iteration   3: 6.446 ops/ms
Iteration   1: 6.631 ops/ms
Iteration   2: 7.188 ops/ms
Iteration   3: 6.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.929 ±(99.9%) 5.117 ops/ms [Average]
  (min, avg, max) = (6.631, 6.929, 7.188), stdev = 0.280
  CI (99.9%): [1.812, 12.046] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.006 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.972 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.330 ±(99.9%) 0.006 ms/op
Iteration   1: 3.956 ±(99.9%) 0.010 ms/op
Iteration   2: 4.007 ±(99.9%) 0.007 ms/op
Iteration   3: 4.176 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.046 ±(99.9%) 2.101 ms/op [Average]
  (min, avg, max) = (3.956, 4.046, 4.176), stdev = 0.115
  CI (99.9%): [1.945, 6.148] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.498 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.004 ms/op
Iteration   1: 3.783 ±(99.9%) 0.007 ms/op
Iteration   2: 3.726 ±(99.9%) 0.007 ms/op
Iteration   3: 3.843 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.784 ±(99.9%) 1.072 ms/op [Average]
  (min, avg, max) = (3.726, 3.784, 3.843), stdev = 0.059
  CI (99.9%): [2.713, 4.856] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.898 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.006 ms/op
Iteration   1: 3.930 ±(99.9%) 0.004 ms/op
Iteration   2: 4.101 ±(99.9%) 0.007 ms/op
Iteration   3: 3.946 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.992 ±(99.9%) 1.722 ms/op [Average]
  (min, avg, max) = (3.930, 3.992, 4.101), stdev = 0.094
  CI (99.9%): [2.271, 5.714] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.245 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.663 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.992 ±(99.9%) 0.012 ms/op
Iteration   1: 4.763 ±(99.9%) 0.010 ms/op
Iteration   2: 4.668 ±(99.9%) 0.010 ms/op
Iteration   3: 4.750 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.727 ±(99.9%) 0.940 ms/op [Average]
  (min, avg, max) = (4.668, 4.727, 4.763), stdev = 0.052
  CI (99.9%): [3.787, 5.667] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.239 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 4.840 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.020 ms/op
Iteration   1: 3.965 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  22.685 ms/op
                 createUser·p0.9999: 25.428 ms/op
                 createUser·p1.00:   25.821 ms/op

Iteration   2: 4.088 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.948 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  12.009 ms/op
                 createUser·p0.9999: 28.350 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   3: 4.086 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.337 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  29.931 ms/op
                 createUser·p0.9999: 32.616 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237116
  mean =      4.046 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 774 
    [ 2.500,  5.000) = 219021 
    [ 5.000,  7.500) = 14618 
    [ 7.500, 10.000) = 1759 
    [10.000, 12.500) = 479 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 68 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.337 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.776 ms/op
     p(95.0000) =      5.383 ms/op
     p(99.0000) =      7.725 ms/op
     p(99.9000) =     23.425 ms/op
     p(99.9900) =     32.089 ms/op
     p(99.9990) =     33.875 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 12.180 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.274 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
Iteration   1: 3.889 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.317 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.324 ms/op
                 existUser·p0.999:  11.517 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   2: 3.911 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.860 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   9.372 ms/op
                 existUser·p0.999:  22.872 ms/op
                 existUser·p0.9999: 31.937 ms/op
                 existUser·p1.00:   32.473 ms/op

Iteration   3: 3.840 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.985 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  12.239 ms/op
                 existUser·p0.9999: 33.795 ms/op
                 existUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247368
  mean =      3.880 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 788 
    [ 2.500,  5.000) = 234009 
    [ 5.000,  7.500) = 9276 
    [ 7.500, 10.000) = 2296 
    [10.000, 12.500) = 659 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 82 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.334 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.045 ms/op
     p(99.9000) =     14.690 ms/op
     p(99.9900) =     32.309 ms/op
     p(99.9990) =     34.179 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 11.318 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.093 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.013 ms/op
Iteration   1: 4.025 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.653 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.619 ms/op
                 getUser·p0.999:  22.413 ms/op
                 getUser·p0.9999: 24.971 ms/op
                 getUser·p1.00:   26.673 ms/op

Iteration   2: 4.036 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   5.702 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  13.759 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   27.591 ms/op

Iteration   3: 3.973 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.768 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.521 ms/op
                 getUser·p0.99:   8.290 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 36.224 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 239195
  mean =      4.011 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 116 
    [ 2.500,  5.000) = 223426 
    [ 5.000,  7.500) = 12652 
    [ 7.500, 10.000) = 2128 
    [10.000, 12.500) = 567 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     20.447 ms/op
     p(99.9900) =     33.961 ms/op
     p(99.9990) =     36.663 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 14.785 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.394 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.096 ±(99.9%) 0.020 ms/op
Iteration   1: 4.940 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.980 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   10.578 ms/op
                 listUser·p0.999:  26.411 ms/op
                 listUser·p0.9999: 30.378 ms/op
                 listUser·p1.00:   31.785 ms/op

Iteration   2: 4.548 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.229 ms/op
                 listUser·p0.999:  20.403 ms/op
                 listUser·p0.9999: 23.983 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   3: 4.721 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.126 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   6.119 ms/op
                 listUser·p0.99:   8.976 ms/op
                 listUser·p0.999:  18.294 ms/op
                 listUser·p0.9999: 26.779 ms/op
                 listUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202806
  mean =      4.731 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 167199 
    [ 5.000,  7.500) = 28808 
    [ 7.500, 10.000) = 5178 
    [10.000, 12.500) = 970 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 132 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.980 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.308 ms/op
     p(95.0000) =      6.316 ms/op
     p(99.0000) =      9.519 ms/op
     p(99.9000) =     21.594 ms/op
     p(99.9900) =     29.478 ms/op
     p(99.9990) =     30.769 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.041 ± 2.876  ops/ms
ClientPb.existUser                       thrpt       3   8.499 ± 1.574  ops/ms
ClientPb.getUser                         thrpt       3   8.236 ± 1.929  ops/ms
ClientPb.listUser                        thrpt       3   6.929 ± 5.117  ops/ms
ClientPb.createUser                       avgt       3   4.046 ± 2.101   ms/op
ClientPb.existUser                        avgt       3   3.784 ± 1.072   ms/op
ClientPb.getUser                          avgt       3   3.992 ± 1.722   ms/op
ClientPb.listUser                         avgt       3   4.727 ± 0.940   ms/op
ClientPb.createUser                     sample  237116   4.046 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.337           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.725           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.425           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.089           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.144           ms/op
ClientPb.existUser                      sample  247368   3.880 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.579           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.736           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.334           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.045           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.690           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.309           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.800           ms/op
ClientPb.getUser                        sample  239195   4.011 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.251           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.603           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.864           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.447           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.961           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.159           ms/op
ClientPb.listUser                       sample  202806   4.731 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.980           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.308           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.519           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.594           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.785           ms/op
